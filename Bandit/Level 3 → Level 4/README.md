# 🌟 Bandit Level 3 → Level 4 🌟

## 🎯 Objetivo del Nivel
La contraseña para el siguiente nivel está almacenada en un archivo oculto en el directorio `inhere`. Utiliza esta contraseña para iniciar sesión en **bandit4** usando SSH y continuar el juego. 🔑

## 🛠️ Comandos que podrías necesitar
- `ls` 🗂️
- `cd` 📂
- `cat` 📜
- `file` 📝
- `du` 📊
- `find` 🔍

## 📝 Pasos para resolver el nivel

1. **Iniciar sesión en Bandit Level 3**: Asegúrate de haber iniciado sesión en el nivel 3 antes de continuar. 👨‍💻

2. **Ir al directorio `inhere`**: Usa el comando `cd` para entrar en el directorio `inhere`, que contiene el archivo oculto con la contraseña.

    ```bash
    cd inhere
    ```

3. **Listar los archivos, incluyendo los ocultos**: Los archivos ocultos en Linux comienzan con un punto (`.`), por lo que necesitas usar la opción `-a` con `ls` para listar todos los archivos, incluidos los ocultos.

    ```bash
    ls -a
    ```

    Busca un archivo oculto que contenga la contraseña. El archivo será de nombre algo como `.hidden` o similar.

4. **Leer el contenido del archivo oculto**: Una vez que encuentres el archivo oculto, usa `cat` para leerlo y obtener la contraseña.

    ```bash
    cat .hidden
    ```

    Esto debería mostrar la contraseña para el siguiente nivel. 🗝️

5. **Iniciar sesión en el siguiente nivel usando SSH**: Ahora que tienes la contraseña para **Bandit Level 4**, usa SSH para conectarte al siguiente nivel. La conexión se realiza mediante el puerto 2220. 🔐

    ```bash
    ssh bandit4@localhost -p 2220
    ```

    Ingresa la contraseña que encontraste en el archivo oculto cuando se te solicite.

6. **Continúa con el juego**: Una vez hayas iniciado sesión, ¡estarás listo para avanzar al siguiente nivel! 🚀

## 📝 Notas
- Los archivos ocultos en Linux comienzan con un punto (`.`), y necesitas usar `ls -a` para verlos.
- No olvides guardar las contraseñas para cada nivel. 📓

¡Disfruta del desafío! 🎮
