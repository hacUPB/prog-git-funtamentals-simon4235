# Para que sirve .gitignore?  

El archivo .gitignore es esencialmente la "lista de invitados" de tu repositorio de Git: le dice al sistema exactamente qué archivos y carpetas debe ignorar y no subir al servidor (como GitHub, GitLab o Bitbucket).  
## Ejemplos:  
  
## 1. Mantener la seguridad (Credenciales)  
Nunca querrás que tus contraseñas, llaves de API o tokens de acceso terminen en un repositorio público.  
  
## 2. Evitar archivos "basura" o temporales  
Tu computadora genera archivos que solo sirven para que el sistema funcione localmente, pero que no son parte del código fuente. Subirlos solo ensucia el proyecto.
  
## 3. Omitir dependencias pesadas  
En lugar de subir gigabytes de librerías que otros pueden descargar fácilmente con un comando, las ignoras para que el repositorio sea ligero.  
  
## 4. Evitar conflictos de compilación  
Los archivos resultantes de compilar tu código (ejecutables o binarios) cambian cada vez que guardas. Si los subes, causarás conflictos innecesarios con tus compañeros de equipo.  