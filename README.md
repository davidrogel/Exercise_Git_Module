# Alumno: David Rogel Pernas

## ¿Qué comando utilizaste en el paso 11? ¿Por qué?

He usado "git reset --hard HEAD~1"

Con reset HEAD~1 vuelvo 1 vez atrás
Y con --hard pierdo todo los cambios

## ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

git reflog para revisar los pasos hecho, copiar el id del commit que me interesa
Luego uso git reset <id del commit> para volver a el

## El Merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

No causa conflicto porque desde styles que es hijo de master no puede hacerse un merge. Sale el mensaje 'Already up to date'.

## El Merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

Si, ya que 'htmlify' y 'styles' tienen diferente contenido

## El Merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

No, porque master ha absorbido a styled y se ha quedado con sus cambios

## ¿Qué comando o comandos utilizaste en el paso 25?

git log --graph

## - El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? 

Si, porque lo único que se está haciendo es mover la rama master a la posición de la rama title.

## - ¿Qué comando o comandos utilizaste en el paso 27?

git reset HEAD~1

## - ¿Qué comando o comandos utilizaste en el paso 28? 

git checkout -- git-nuestro.md

## - ¿Qué comando o comandos utilizaste en el paso 29?

git branch -D title 

## - ¿Qué comando o comandos utilizaste en el paso 30? 

git reflog para conocer el id del commit que me interesa
git reset <id del commit>

## - ¿Qué comando o comandos usaste en el paso 32?

git log, para mirar el id del primer commit 
git checkout <id del commit>
me he quedado en detached HEAD

## - ¿Qué comando o comandos usaste en el punto 33?

git reflog, buscar el id del commit que me interesa
git checkout <id del commit>


