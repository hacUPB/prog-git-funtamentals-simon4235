# Uso de la Consola: Navegación, Creación y Gestión de Archivos

!()

La consola, también conocida como terminal o línea de comandos, es una interfaz textual que nos permite interactuar directamente con el sistema operativo. Aunque puede parecer intimidante al principio, dominarla es fundamental para el desarrollo de software, la administración de sistemas y el trabajo con herramientas como Git.

En esta unidad, aprendimos a navegar por el sistema de archivos, crear directorios y gestionar archivos básicos utilizando comandos. Esto nos da un control más preciso y a menudo más rápido que una interfaz gráfica.

## Conceptos Clave

* **Directorio (Folder):** Una ubicación en el sistema de archivos que puede contener otros archivos y directorios.
* **Directorio Raíz:** El directorio más alto en la jerarquía del sistema de archivos, representado a menudo por `/` (en sistemas Unix/Linux/macOS) o `C:\` (en Windows).
* **Directorio Actual de Trabajo (Current Working Directory):** El directorio en el que te encuentras posicionado en un momento dado dentro de la consola.
* **Ruta Absoluta:** La dirección completa de un archivo o directorio desde el directorio raíz.
* **Ruta Relativa:** La dirección de un archivo o directorio desde el directorio actual de trabajo.

## Principales Comandos Utilizados

Aquí tienes un listado de los comandos más importantes que hemos cubierto:

1.  **`pwd` (Print Working Directory):** Muestra la ruta absoluta del directorio actual de trabajo.
    ```bash
    pwd
    ```

2.  **`ls` (List):** Lista el contenido del directorio actual. Con opciones como `-l` (formato largo) o `-a` (incluir archivos ocultos).
    ```bash
    ls -la
    ```

3.  **`cd` (Change Directory):** Cambia el directorio actual.
    * `cd <nombre_directorio>`: Entra en un directorio específico.
    * `cd ..`: Sube un nivel en la jerarquía de directorios.
    * `cd ~`: Va al directorio de inicio del usuario.
    * `cd /`: Va al directorio raíz.
    ```bash
    cd proyectos
    cd ..
    ```

4.  **`mkdir` (Make Directory):** Crea uno o varios directorios.
    ```bash
    mkdir mi_nuevo_directorio
    ```
5.  **`touch` (Crear Archivo Vacío):** Crea un archivo vacío (en Linux/macOS). En Windows, puedes usar `type nul > archivo.txt` o `New-Item archivo.txt` en PowerShell.
    ```bash
    touch mi_archivo.txt
    ```

8.  **`rm` (Remove):** Borra archivos o directorios. ¡**Cuidado** con este comando, ya que los archivos borrados no van a la papelera de reciclaje!
    * `rm archivo.txt`: Borra un archivo.
    * `rm -r directorio/`: Borra un directorio y todo su contenido de forma recursiva.
    ```bash
    rm archivo_a_borrar.txt
    rm -r directorio_a_borrar/
    ```

9.  **`cat` (Concatenate and Print):** Muestra el contenido de uno o varios archivos en la consola.
    ```bash
    cat mi_archivo.txt
    ```