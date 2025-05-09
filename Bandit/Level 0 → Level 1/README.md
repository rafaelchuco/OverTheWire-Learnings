# 🌟 Bandit Level 0 → Level 1 🌟

## 🎯 Objetivo del Nivel
La contraseña para el siguiente nivel está almacenada en un archivo llamado `readme` ubicado en el directorio home. Usa esta contraseña para iniciar sesión en **bandit1** usando SSH y continuar el juego. 🔑

## 🛠️ Comandos que podrías necesitar
- `ls` 🗂️
- `cd` 📂
- `cat` 📜
- `file` 📝
- `du` 📊
- `find` 🔍

## 📝 Pasos para resolver el nivel

1. **Iniciar sesión en Bandit Level 0**: Ya deberías estar conectado en este nivel, ya que es el punto de inicio. 👨‍💻

2. **Buscar el archivo llamado `readme`**: Este archivo contiene la contraseña para el siguiente nivel. Usa el comando `ls` para listar los archivos del directorio y encontrar el archivo `readme`.

    ```bash
    ls
    ```

3. **Leer el contenido del archivo `readme`**: Usa el comando `cat` para ver el contenido del archivo y obtener la contraseña.

    ```bash
    cat readme
    ```

    La contraseña aparecerá en la terminal. 🗝️

4. **Iniciar sesión en el siguiente nivel usando SSH**: Ahora que tienes la contraseña para **Bandit Level 1**, usa SSH para conectarte al siguiente nivel. La conexión se realiza mediante el puerto 2220. 🔐

    ```bash
    ssh bandit1@localhost -p 2220
    ```

    Ingresa la contraseña que encontraste en el archivo `readme` cuando se te solicite.

5. **Continúa con el juego**: Una vez hayas iniciado sesión, ¡estarás listo para avanzar al siguiente nivel! 🚀

## 📝 Notas
- Asegúrate de guardar las contraseñas para cada nivel, ya que no se guardan automáticamente. 📓
- A medida que los niveles se vuelven más desafiantes, tomar notas detalladas sobre cómo resolver cada reto te será muy útil. ✍️

¡Disfruta del juego! 🎮
