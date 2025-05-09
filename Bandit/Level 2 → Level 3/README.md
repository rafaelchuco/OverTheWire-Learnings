# 🌟 Bandit Level 2 → Level 3 🌟

## 🎯 Objetivo del Nivel
La contraseña para el siguiente nivel está almacenada en un archivo llamado `spaces in this filename`, ubicado en el directorio home. Utiliza esta contraseña para iniciar sesión en **bandit3** usando SSH y continuar el juego. 🔑

## 🛠️ Comandos que podrías necesitar
- `ls` 🗂️
- `cd` 📂
- `cat` 📜
- `file` 📝
- `du` 📊
- `find` 🔍

## 📚 Material de Lectura Útil
- Buscar en Google: **"spaces in filename"**

## 📝 Pasos para resolver el nivel

1. **Iniciar sesión en Bandit Level 2**: Asegúrate de haber iniciado sesión en el nivel 2 antes de continuar. 👨‍💻

2. **Buscar el archivo llamado `spaces in this filename`**: Este archivo contiene espacios en su nombre, lo que puede hacer que sea difícil de acceder. Usa el comando `ls` para listar los archivos en el directorio home.

    ```bash
    ls
    ```

    El archivo que buscas se llama `spaces in this filename`, y debido a los espacios, necesitas usar comillas o barras invertidas.

3. **Leer el contenido del archivo**: Usa `cat` para leer el archivo. Como tiene espacios en el nombre, debes usar comillas alrededor del nombre del archivo o barras invertidas para escapar los espacios.

    Opción 1 (con comillas):

    ```bash
    cat "spaces in this filename"
    ```

    Opción 2 (con barras invertidas):

    ```bash
    cat spaces\ in\ this\ filename
    ```

    Esto debería mostrar la contraseña para el siguiente nivel. 🗝️

4. **Iniciar sesión en el siguiente nivel usando SSH**: Ahora que tienes la contraseña para **Bandit Level 3**, usa SSH para conectarte al siguiente nivel. La conexión se realiza mediante el puerto 2220. 🔐

    ```bash
    ssh bandit3@localhost -p 2220
    ```

    Ingresa la contraseña que encontraste en el archivo `spaces in this filename` cuando se te solicite.

5. **Continúa con el juego**: Una vez hayas iniciado sesión, ¡estarás listo para avanzar al siguiente nivel! 🚀

## 📝 Notas
- Los archivos con espacios en su nombre requieren que uses comillas o barras invertidas para acceder a ellos correctamente.
- No olvides guardar las contraseñas para cada nivel. 📓

¡Disfruta del desafío! 🎮
