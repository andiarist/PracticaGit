- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
git reset --hard HEAD~1, para perder los cambios en el working copy
- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
git reflog para buscar el hash del commit
git reset hashDelCommit para volver a él
git restore git-nuestro para descartar los cambios del working copy y quedarme con el commit
- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
No causa conflicto porque no tiene que mover ningún puntero
- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Sí que causa conflictos porque hemos hecho cambios en el mismo archivo, mismas lineas
- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No
- ¿Qué comando o comandos utilizaste en el paso 25?
git log --graph
- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Si, porque las ramas forman una lista
- ¿Qué comando o comandos utilizaste en el paso 27?
git reset HEAD~1
- ¿Qué comando o comandos utilizaste en el paso 28?
git restore git-nuestro
- ¿Qué comando o comandos utilizaste en el paso 29?
git branch -D title
- ¿Qué comando o comandos utilizaste en el paso 30?
git reflog para buscar el hash
git reset hashDelMerge
git restore git-nuestro
- ¿Qué comando o comandos usaste en el paso 32?
git reflog para buscar el hash
git checkout hashPrimerCommit
- ¿Qué comando o comandos usaste en el punto 33?
git checkout master
