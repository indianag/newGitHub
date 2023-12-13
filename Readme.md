//En mi rama local//
git init
git add .
git commit -m
git status
git push
//comandos arriba, sube mis cambios locales a mi rama remota//

//para MERGEAR//
git checkout main
git pull (actualiza main local con los cambios de la main remota)
git status (reviso que todo funcione)
git merge mi rama
RESUELVO CONFLICTOS
git status (reviso que funcione todo LOCAL Y REMOTO)
git add .
git commit -m
git push
//Esto actualizara la rama main remota con los cambios de mi rama//

git remote add //enlazar repositorio local con remoto
git push //subir cambios al repositorio remoto

//se ha ignorado cargar esta carpeta a mi repositorio

//se ha presentado un conflicto ya que en la rama1 de mi proyecto 
he eliminado la funcion suma y guarde cambios en mi rama main, 
luego cuando modifico mi rama2 y actualizo con la main 
esta me avisa que esa funcion ya no existe y crea un conflicto para actualizar
de la misma manera me pregunta con cual de mis cambios quiero seguir trabajando//