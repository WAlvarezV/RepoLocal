//Crear repositorio local
1 crear la carpeta del repositorio
2 abrir la carpeta
3 iniciar al consola de git bash
4 git init //iniciar un repositorio en la carpeta seleccionada
5 agregar al menos un archivo al repositorio local
6 git add nombre_primer_archivo
7 git commit -m "initial commit" //commit inicial

8 //Crear repositorio github/bitbucket
9 git add remote origin https://github.com/WAlvarezV/RepoLocal.git url del repositorio creado
10 git push -u origin master

//comandos git
//verificar estado del repositorio local
git status
//agregar cambios
git add nombre_archivo_modificado
//agregar todos los cambios si se tiene un archivo .gitignore
git add .
//confirmar cambios
git commit -m "mensaje descriptivo del commit"
//sincronización de cambios remoto a local
git pull origin nombre_rama
//sincronización de cambios local a remoto
git push origin nombre_rama
