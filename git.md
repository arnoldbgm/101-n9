# Guía para usar Git y crear un proyecto HTML desde cero

## **Comandos básicos de Git que debes conocer** 🛠️

<img src="https://github.com/user-attachments/assets/9cca2c2a-ea87-4676-9edd-e17584a20b18" alt="image" width="300">

Antes de comenzar, estos son los comandos esenciales que usarás al trabajar con Git:

1. **`git init`** 🚀
   Inicializa un repositorio Git en la carpeta actual.
   Sirve para convertir una carpeta en un repositorio donde podrás versionar tus cambios.

2. **`git add`** ➕
   Agrega archivos al área de preparación (stage).
   Esto significa que estás diciendo a Git qué archivos quieres incluir en el próximo commit.

   **Ejemplo**:
   ```bash
   $ git add archivo.txt

3. **`git commit -m "[mensaje]"`** 📜
    
    Guarda los cambios en el historial de tu repositorio con un mensaje descriptivo.
    
    Es como tomar una "foto" del estado actual de tus archivos.
    
    **Ejemplo**:
    
    ```bash
    $ git commit -m "Añadí el archivo index.html"
    
    ```
    
4. **`git status`** 🔍
    
    Muestra el estado del repositorio:
    
    - Qué archivos han sido modificados.
    - Cuáles están en el área de preparación.
    - Si hay algo listo para ser guardado con un commit.
    
    **Ejemplo**:
    
    ```bash
    $ git status
    
    ```
    
5. **`git log`** 📚
    
    Muestra el historial de commits realizados en tu repositorio.
    
    Es útil para ver qué cambios se hicieron y cuándo.
    
    **Ejemplo**:
    
    ```bash
    $ git log
    
    ```
    
6. **`git push`** ⬆️
    
    Sube tus cambios del repositorio local al repositorio remoto (por ejemplo, GitHub).
    
    **Ejemplo**:
    
    ```bash
    $ git push origin main
    
    ```
    
7. **`git clone [URL]`** 📥
    
    Crea una copia exacta de un repositorio remoto en tu máquina local.
    
    **Ejemplo**:
    
    ```bash
    $ git clone https://github.com/usuario/repositorio.git
    
    ```
    

---

## **Paso a paso para crear un proyecto HTML versionado con Git**

1. **Crea una carpeta para tu proyecto** 📂
    
    Usa `mkdir` para crear una nueva carpeta donde guardarás tu proyecto.
    
    **Ejemplo**:
    
    ```bash
    $ mkdir mi_primer_proyecto
    
    ```
    
2. **Entra en la carpeta creada** 🔍
    
    Cambia al directorio recién creado usando `cd`.
    
    **Ejemplo**:
    
    ```bash
    $ cd mi_primer_proyecto
    
    ```
    
3. **Abre la carpeta en Visual Studio Code** 💻
    
    Usa `code .` para abrir la carpeta en VS Code.
    
    **Ejemplo**:
    
    ```bash
    $ code .
    
    ```
    
    Ahora tendrás la carpeta abierta en el editor.
    
4. **Crea un archivo HTML en VS Code** 🌐
    
    En el explorador de archivos de VS Code, haz clic derecho y selecciona **Nuevo Archivo**. Nómbralo como:
    
    ```html
    index.html
    
    ```
    
    **Contenido básico sugerido para tu archivo HTML**:
    
    ```html
    <!DOCTYPE html>
    <html lang="es">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Mi Primer Proyecto</title>
    </head>
    <body>
        <h1>¡Hola, mundo!</h1>
        <p>Este es mi primer proyecto HTML.</p>
    </body>
    </html>
    
    ```
    
5. **Inicializa un repositorio Git** 🚀
    
    Para comenzar a versionar tu trabajo, inicializa un repositorio con `git init`.
    
    **Ejemplo**:
    
    ```bash
    $ git init
    
    ```
    
6. **Agrega el archivo HTML al área de preparación** ➕
    
    Usa `git add` para agregar los archivos que quieras rastrear.
    
    **Ejemplo**:
    
    ```bash
    $ git add index.html
    
    ```
    
7. **Haz un commit con un mensaje descriptivo** 📜
    
    Guarda tus cambios en el repositorio con `git commit`.
    
    **Ejemplo**:
    
    ```bash
    $ git commit -m "Agregué el archivo index.html con la estructura básica"
    
    ```
    
8. **Crea un repositorio remoto en GitHub** 🌐
    
    Ve a [GitHub](https://github.com/), inicia sesión y crea un nuevo repositorio vacío llamado `mi_primer_proyecto`.
    
    Copia la URL del repositorio remoto.
    
9. **Conecta tu repositorio local con el remoto** 🔗
    
    Usa `git remote add origin` para enlazar tu repositorio local con el de GitHub.
    
    **Ejemplo**:
    
    ```bash
    $ git remote add origin https://github.com/usuario/mi_primer_proyecto.git
    
    ```
    
10. **Sube tus cambios al repositorio remoto** ⬆️
    
    Usa `git push` para subir tus cambios a GitHub.
    
    **Ejemplo**:
    
    ```bash
    $ git push -u origin main
    
    ```
    
    Nota: Si tu rama local se llama `master`, reemplaza `main` por `master`.
    
11. **Verifica tu proyecto en GitHub** 🧭
    
    Ve a tu repositorio en GitHub y verifica que el archivo `index.html` esté ahí.
    

---

### **¡Listo!** 🎉

Ahora tienes un proyecto HTML básico creado, versionado con Git y almacenado en GitHub. ¡Un gran paso para comenzar tu carrera como desarrollador! 😊
