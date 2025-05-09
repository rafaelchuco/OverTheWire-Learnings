# 🌟 Bandit Level 1 → Level 2 🌟

## 🎯 Objetivo del Nivel
La contraseña para el siguiente nivel está almacenada en un archivo llamado `-`, ubicado en el directorio home. Utiliza esta contraseña para iniciar sesión en **bandit2** usando SSH y continuar el juego. 🔑

## 🛠️ Comandos que podrías necesitar
- `ls` 🗂️
- `cd` 📂
- `cat` 📜
- `file` 📝
- `du` 📊
- `find` 🔍

## 📚 Material de Lectura Útil
- Buscar en Google: **"dashed filename"**
- Guía Avanzada de Bash - Capítulo 3 - Caracteres Especiales

## 📝 Pasos para resolver el nivel

1. **Iniciar sesión en Bandit Level 1**: Asegúrate de haber iniciado sesión en el nivel 1 antes de continuar. 👨‍💻

2. **Buscar el archivo llamado `-`**: Este archivo tiene un nombre especial debido al guion. Usa el comando `ls` para listar los archivos en el directorio home.

    ```bash
    ls
    ```

    El archivo que buscas se llama `-`, pero debido al nombre especial, necesitarás un pequeño truco.

3. **Leer el contenido del archivo `-`**: Como el archivo se llama simplemente `-`, no puedes usar directamente el comando `cat -`. En su lugar, puedes usar una de estas opciones:

    ```bash
    cat ./-
    ```

    O también:

    ```bash
    cat -- -
    ```

    Esto debería mostrar la contraseña para el siguiente nivel. 🗝️

4. **Iniciar sesión en el siguiente nivel usando SSH**: Ahora que tienes la contraseña para **Bandit Level 2**, usa SSH para conectarte al siguiente nivel. La conexión se realiza mediante el puerto 2220. 🔐

    ```bash
    ssh bandit2@localhost -p 2220
    ```

    Ingresa la contraseña que encontraste en el archivo `-` cuando se te solicite.

5. **Continúa con el juego**: Una vez hayas iniciado sesión, ¡estarás listo para avanzar al siguiente nivel! 🚀

## 📝 Notas
- Los archivos con nombres que comienzan con `-` pueden ser complicados de manejar en la terminal, pero con el prefijo `./` o el uso de `--`, puedes acceder a ellos fácilmente.
- No olvides guardar las contraseñas para cada nivel. 📓

¡Disfruta del desafío! 🎮
