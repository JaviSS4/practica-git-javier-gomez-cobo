- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
"git reset --hard HEAD~1", porque en el paso te especifica que también se tienen que perder los cambios realizados en la working copy.

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
"git reset --hard", tras haber visto la id de mi anterior commit con el comando ""git reflog"".

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
Se podría decir que no, pero me sale el mensaje "already up to date", porque en este momento el HEAD de la rama master es un padre de la rama styled. 

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Sí, porque hemos querido unir dos ramas diferentes que tienen 2 versiones distitntas de la misma línea en el mismo archivo.

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No, porque ya le había hecho merge a las 2 ramas anteriormente.

- ¿Qué comando o comandos utilizaste en el paso 25?
git log --graph

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
No, porque teníamos ya un commit en las 2 ramas separadas.

- ¿Qué comando o comandos utilizaste en el paso 27?
git reset HEAD~1

- ¿Qué comando o comandos utilizaste en el paso 28?
git restore

- ¿Qué comando o comandos utilizaste en el paso 29?
git branch -D

- ¿Qué comando o comandos utilizaste en el paso 30?
git reset --hard, tras usar git reflog

- ¿Qué comando o comandos usaste en el paso 32?
git reflog, git reset 

- ¿Qué comando o comandos usaste en el punto 33?
git reflog, git reset

 