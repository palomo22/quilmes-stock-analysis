##
1.Genero la estructura del proyecto a traves la termina de visual studio:
 crear carpeta principal, crear subcarpetas, crear archivos iniciales de cada subcarpeta
  crear los archivos .gitignore, README y requirements.
##
2. Creo el entorno virtual: es el entorno donde se va a desarrollar el proyecto puntual: incluye codigo python, las librerias instaladas con pip, Scripts ejecutables, y la configuracion del entorno. 
###
3. .gitignore : le indico que no es necesario subir la carpeta VENV, la del entorno virtual. No es una buena practica. Se aisla todo lo que se puede generar localmente, por eso se utiliza el archivo requeriments.txt, que a traves de un camando especifico se puede ejecutar para crear el entorno virtual.
##
4. GIT y GITHUB : Git me permite mantener actualizas las versiones del proyecto y luego subirlos a github. 'Git Init' para convertir la carpeta a un repositorio local: 'git add .' para agregar todos los archivos al repositorio; 'git commit' guardar cambios, se hace el primer commit.
En GITHUB 'https://github.com/new' creo el repositorio remoto. Luego con las instrucciones: 
'git remote add origin https://github.com/usuario/nombreproyecto.git ' para vincular el repositorio local con el remoto.
'git branch -m main' me aseguro que mi rama se llama main.Es importante para asegurarme que el commit se haga sobre la principal.
'push -u origin main' : para subir el primer commit.
5. Subir cambios a github. Primero se realizan en el repositorio local y luego a traves de push al remoto:
'git status' para verificar los cambios, te indica que archivo fue cambiado.
'git add 'archivo'' esto lo sube al staging area, listo para ser confirmado.
'git commit -m 'aaaxxxsnnsk' confirma el cambio localmente.
'git push origin main' envia desde mi repositorio local al remoto github, a la rama ´main'