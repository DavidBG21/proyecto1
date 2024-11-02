# Práctica 1: Introducción a Git y GitHub
### _En esta práctica se espera utilizar las herramientas de control de versiones como Git, usando comandos básisos y finalmente alojar estos cambios en GitHub_
### _De esta manera se logra aprender y practicar los comandos básicos e identificar sus principales funcionalidades_

### Instrucciones de uso:
- Es necesario instalar [Python](https://www.python.org/downloads/) v3.0+ para ejecutar archivos .py.
- Abrir una terminal de windows.
- Colocarte en la ruta donde se encuentra el archivo .py
- Ejecutar con el comando "python HolaMundo.py".
- Se imprimirá el mensaje correspondiente.

### Comandos utilizados durante la práctica

Para poder crear los cambios locales (Git) se usaron los siguientes comandos:

- [git init] - Crear un repositorio de Git vacío o reinicializar uno ya existente.
- [git remote] - Administrar un conjunto de repositorios rastreados.
- [git add] - Pasamos TODOS los archivos del área de trabajo (working directory) al área de preparación (stagin área). 
- [git commit] - Ya con los archivos seleccionados, se procede a enviar al repositorio local (local repo). 

Finalmente para poder alojar los cambios locales (Git) en un servidor remoto (GitHub) se usó:

- [git push] - Actualizar referencias remotas junto con objetos asociados, es decir subir todos los cambios que están en el repositorio local (Todos los commits realizados) al remoto (remote repo). 

### Notas sobre el archivo ".gitignore"

El archivo contiene una lista correspondiente a archivos que serán ignorados por el gestor de control de versiones, y como Git tiene contexto de linux podemos usar ciertos comandos de manupulación de ficheros como "*.log" que es para omitir todos los archivos sin importar nombre pero que terminen en extensión .log 
```sh
#Ignora el archivo "debug.log"
/debug.log
```
Finalmente para verificar que el archivo no sea tomado en cuenta, se puede usar el comando "git status" y en el nombre del archivo no debe estar incluido en el área de "untracked files".

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [git init]: <https://git-scm.com/docs/git-init>
   [git remote]: <https://git-scm.com/docs/git-remote>
   [git add]: <https://git-scm.com/docs/git-add>
   [git commit]: <https://git-scm.com/docs/git-commit>
   [git push]: <https://git-scm.com/docs/git-push>

