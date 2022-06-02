# GIT Desarrollo Colaborativo

Esto es una guía creada para facilitar el entendimiento e implementación de la herramienta conocida como git, desarrollada por Linus Torvalds, y cuya finalidad es el control de versiones de los diferentes proyectos que realicemos.

## Configuración inicial

Comandos que debemos utilizar para crear un proyecto con git, como para establecer la configuración de nuestro nombre y correo a utilizar en cada una de las confirmaciones de cambios. El parametro *global* indica que dicha configuración aplica para todos los proyectos del mismo usuario.

* **git init** inicializa el repositorio en el directorio actual
* **git config --global user.name** `username`: Define de manera global el nombre con el que nos identificamos.
* **git config --global user.enmail** `email`: Define el correo de contacto para las confirmaciones de cambios.