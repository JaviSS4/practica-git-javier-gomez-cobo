- �Qu� comando utilizaste en el paso 11? �Por qu�?
"git reset --hard HEAD~1", porque en el paso te especifica que tambi�n se tienen que perder los cambios realizados en la working copy.

- �Qu� comando o comandos utilizaste en el paso 12? �Por qu�?
"git reset --hard", tras haber visto la id de mi anterior commit con el comando ""git reflog"".

- El merge del paso 13, �Caus� alg�n conflicto? �Por qu�?
Se podr�a decir que no, pero me sale el mensaje "already up to date", porque en este momento el HEAD de la rama master es un padre de la rama styled. 

- El merge del paso 19, �Caus� alg�n conflicto? �Por qu�?
S�, porque hemos querido unir dos ramas diferentes que tienen 2 versiones distitntas de la misma l�nea en el mismo archivo.

- El merge del paso 21, �Caus� alg�n conflicto? �Por qu�?
No, porque ya le hab�a hecho merge a las 2 ramas anteriormente.

- �Qu� comando o comandos utilizaste en el paso 25?
git log --graph

- El merge del paso 26, �Podr�a ser fast forward? �Por qu�?
No, porque ten�amos ya un commit en las 2 ramas separadas.

- �Qu� comando o comandos utilizaste en el paso 27?
git reset HEAD~1

- �Qu� comando o comandos utilizaste en el paso 28?
git restore

- �Qu� comando o comandos utilizaste en el paso 29?
git branch -D

- �Qu� comando o comandos utilizaste en el paso 30?
git reset --hard, tras usar git reflog

- �Qu� comando o comandos usaste en el paso 32?
git reflog, git reset 

- �Qu� comando o comandos usaste en el punto 33?
git reflog, git reset

 