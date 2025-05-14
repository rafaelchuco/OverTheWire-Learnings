# 🔐 Bandit Level 5 → Level 6

## 🎯 Objetivo del Nivel

El objetivo de este nivel es encontrar la contraseña para el siguiente nivel. La contraseña está almacenada en un archivo dentro del directorio `inhere` y tiene las siguientes propiedades:

- 📄 **Legible para humanos**
- 📏 **Tamaño**: 1033 bytes
- 🚫 **No ejecutable**

## 🛠️ Comandos necesarios

Estos son los comandos que puedes necesitar para resolver este nivel:

- `ls` 🔍
- `cd` 🔄
- `cat` 📖
- `file` 📝
- `du` 💾
- `find` 🔎

## 📝 Pasos para resolver el nivel

### 1. 🧭 Navega al directorio `inhere`:
Primero, entra al directorio `inhere` donde se encuentra el archivo con la contraseña.

```bash
cd inhere
```

### 2. 📂 Lista los archivos en el directorio:

Usa `ls -l` para listar los archivos y ver sus permisos, tamaños y nombres.

```bash
ls -l
```


### 3. 🔍 Encuentra el archivo que cumpla con las condiciones:

Usa el comando `find` para localizar un archivo que tenga las siguientes características:

* **Legible para humanos** 📄
* **Tamaño de 1033 bytes** 📏
* **No ejecutable** 🚫

Ejecuta el siguiente comando:

```bash
find . -type f -size 1033c -exec file {} \; | grep "text"
```

**Explicación**:

* `find .`: Comienza la búsqueda en el directorio actual (`inhere`).
* `-type f`: Solo busca archivos (no directorios).
* `-size 1033c`: Busca archivos de exactamente 1033 bytes.
* `-exec file {} \;`: Ejecuta el comando `file` en cada archivo encontrado para verificar si es legible.
* `grep "text"`: Filtra los archivos que son legibles (de tipo texto).

### 4. 📖 Muestra el contenido del archivo:

Una vez que encuentres el archivo correcto, usa `cat` para ver su contenido y encontrar la contraseña:

```bash
cat ./inhere/maybehere07/.file2
```


## 🎉 Resultado

La contraseña para el siguiente nivel debería aparecer al ejecutar el comando `cat` en el archivo correcto. ¡Felicidades! 🎉🚀
