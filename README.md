# hyperblog
* creado por el super TEAM
Un  blog super para el curso de Platzi
git status
git add
git commit -m 
git config --list
git config --list --show-origin


// doble gion indica usar una palbra global y un gion un comando

  561  git config --global user.name "Alberth Apaza"
  562  git config --global user.mail "maikeru.bash@gmail.com"

git log // toda la historia de un achivo


git diff // mas el cofigo del log

// no hay vuelta atras
git reset  // log // --hard  : esta borrando toda la informacion en el area de staging
git reset  // log //--soft  : mantiene los archivos en el area de staging pasa que podamos aplicar nuestros ultimos cambios pero desde un commit anterior

git reset --soft: borra todo el historial y los registros del Git pero guardamos los cambios  que tengamos en Staging 
git reset --hard : borra todo absolutamente todo.
git show 

git branch // daber en que rama te encuentras 


git cloen url_del_servidor
git push: mandar cambios al servidor remoto.
git fetch: traer actualizaciones del servidor remoto y guardarlas en nuestro remositorio local
git merge: combinar los ultimos cambios del servidor remoto y  nuestro directorio de trabajo.
git pull: git fetch + git merge
