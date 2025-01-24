# Ejercicios de Terminal para Practicar

## Ejercicio 1: Navegación básica
1. Crea un directorio llamado **proyecto**.  
   **Comando:** `mkdir proyecto`
2. Entra al directorio **proyecto**.  
   **Comando:** `cd proyecto`
3. Vuelve al directorio anterior.  
   **Comando:** `cd ..`
4. Crea una nueva carpeta llamada **documentos** dentro de **proyecto**.  
   **Comando:** `mkdir documentos`
5. Dentro de **documentos**, crea otra carpeta llamada **imagenes**.  
   **Comando:** `mkdir imagenes`
6. Lista todos los directorios y archivos dentro de **proyecto**.  
   **Comando:** `ls`

---

## Ejercicio 2: Archivos y directorios
1. Crea un archivo vacío llamado **notas.txt** en el directorio **documentos**.  
   **Comando:** `touch documentos/notas.txt`
2. Crea un archivo llamado **instrucciones.txt** dentro de **imagenes**.  
   **Comando:** `touch imagenes/instrucciones.txt`
3. Mueve el archivo **notas.txt** de **documentos** a **imagenes**.  
   **Comando:** `mv documentos/notas.txt imagenes/`
4. Elimina el archivo **instrucciones.txt** en **imagenes**.  
   **Comando:** `rm imagenes/instrucciones.txt`
5. Copia el archivo **notas.txt** a la carpeta **documentos**.  
   **Comando:** `cp imagenes/notas.txt documentos/`

---

## Ejercicio 3: Visualización y edición
1. Crea un archivo con contenido utilizando `echo`:  
   **Comando:** `echo "Bienvenidos al proyecto final" > proyecto.txt`
2. Visualiza el contenido de **proyecto.txt** con el comando `cat`.  
   **Comando:** `cat proyecto.txt`
3. Abre el archivo **proyecto.txt** con el editor de texto predeterminado de la terminal (por ejemplo, usando Visual Studio Code).  
   **Comando:** `code .`
4. Añade más texto al archivo **proyecto.txt** usando el comando `echo`.  
   **Comando:** `echo "Avances de la primera semana" >> proyecto.txt`
5. Muestra el contenido actualizado del archivo con `cat`.  
   **Comando:** `cat proyecto.txt`

---

## Ejercicio 4: Búsqueda y filtrado
1. Crea varios archivos de texto con nombres como **nota1.txt**, **nota2.txt**, **nota3.txt** en el directorio **documentos**.  
   **Comando:** `touch documentos/nota{1..3}.txt`
2. Lista todos los archivos dentro de **documentos** que contienen "nota".  
   **Comando:** `ls | grep nota`
3. Lista todos los archivos dentro del directorio actual con la extensión **.txt**.  
   **Comando:** `ls *.txt`
