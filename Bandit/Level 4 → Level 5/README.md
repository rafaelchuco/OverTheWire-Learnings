# 🌟 Bandit Level 4 → Level 5 🌟

## 🎯 Objetivo del Nivel
La contraseña para el siguiente nivel está almacenada en el único archivo legible por humanos en el directorio `inhere`. Utiliza esta contraseña para iniciar sesión en **bandit5** usando SSH y continuar el juego. 🔑

**Consejo**: Si tu terminal está desordenado o tiene problemas de visualización, puedes intentar usar el comando `reset`. 🔄

## 🛠️ Comandos que podrías necesitar
- `ls` 🗂️
- `cd` 📂
- `cat` 📜
- `file` 📝
- `du` 📊
- `find` 🔍

## 📝 Pasos para resolver el nivel

1. **Iniciar sesión en Bandit Level 4**: Asegúrate de haber iniciado sesión en el nivel 4 antes de continuar. 👨‍💻

2. **Ir al directorio `inhere`**: Usa el comando `cd` para entrar en el directorio `inhere`, que contiene el archivo legible por humanos con la contraseña.

    ```bash
    cd inhere
    ```

3. **Listar los archivos**: Usa el comando `ls` para listar los archivos en el directorio `inhere`. Deberías ver varios archivos, pero solo uno será legible por humanos.

    ```bash
    ls
    ```

    El resultado puede verse algo así:

    ```bash
    -file00  -file01  -file02  -file03  -file04  -file05  -file06  -file07  -file08  -file09
    ```

4. **Comprobar los archivos**: Usa el comando `file` para verificar qué archivo es legible por humanos.

    ```bash
    file <nombre_del_archivo>
    ```

    El archivo legible debería ser algo como un archivo de texto plano. Una vez que lo encuentres, procede al siguiente paso.

5. **Leer el contenido del archivo**: Una vez que hayas encontrado el archivo legible por humanos, usa el comando `cat` para ver su contenido.

    ```bash
    cat <nombre_del_archivo>
    ```

    Esto debería mostrarte la contraseña para el siguiente nivel. 🗝️

6. **Iniciar sesión en el siguiente nivel usando SSH**: Ahora que tienes la contraseña para **Bandit Level 5**, usa SSH para conectarte al siguiente nivel. La conexión se realiza mediante el puerto 2220. 🔐

    ```bash
    ssh bandit5@localhost -p 2220
    ```

    Ingresa la contraseña que encontraste en el archivo legible cuando se te solicite.

7. **Continúa con el juego**: Una vez hayas iniciado sesión, ¡estarás listo para avanzar al siguiente nivel! 🚀

## 📝 Notas
- El archivo legible por humanos será el único que puedas abrir con `cat` sin ver caracteres extraños.
- Usa el comando `reset` si tu terminal tiene problemas de visualización. 🔄
- No olvides guardar las contraseñas para cada nivel. 📓

¡Disfruta del desafío! 🎮
