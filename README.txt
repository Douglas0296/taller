1-Creación del proyecto: Me dirigí a la página web de Spring Initializr para crear un proyecto en Java con Spring Boot.

2-Configuración del entorno: Abrí el proyecto en Visual Studio Code.

3-Usé el comando git init para inicializar un repositorio vacío en la carpeta del proyecto.

4-Creé una nueva rama llamada feature con git checkout -b feature.

5-Creé un archivo llamado archivo.txt y añadí contenido básico y añadí el archivo al area de prepación

6-Realicé el primer commit con git commit -m "Commit inicial".

7-Agregué más texto al archivo archivo.txt y realicé varios commits, como el segundo y tercer commit en la rama feature.

8-Creé una rama llamada hotfix para realizar una corrección urgente.

9-Después de la corrección, realicé un commit con el mensaje "Hotfix".

10-Durante un intento de realizar un merge entre las ramas feature y master, surgieron conflictos en el archivo conflicto.txt.

11-Resolví el conflicto y realicé un commit con el mensaje "Conflicto resuelto" la solución abrir el archivo conflicto.txt y me aparecia lo soguiente:

<<<<<<< HEAD
Cambio en master
=======
Cambio en feature
>>>>>>> feature

Debia escoger que eliminar y que dejar para resolver el conflicto al final elimine el texto y deje el siguiente "Cambios de la rama master y de la rama feature"
agregue el archivo nuevamente al area de preparación y realice el commit final para confirmar los cambios