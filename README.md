- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
Utilice **git reset --hard HEAD~1** porque modifica tambien el working copy dejandolo como estaba antes de realizar los cambios.
- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
He utilizado **git reset --hard** con la referencia que he obtenido con **git reflog** en el commit inmediatamente anterior y lo he usado en lugar de **git checkout**porque queria que se produjeran los cambios pertinentes en el historial de la rama sobre la que estaba trabajando.
- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
No, porque únicamente ha habido cambios de estilo.
- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Sí, por que los cambios se solapan en el contenido de los archivos.
- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No, porque únicamente hemos añadido un título al inicio del archivo.
- ¿Qué comando o comandos utilizaste en el paso 25?
primero genere un alias con **git config alias.grafo "log --graph --decorate --pretty=online" y luego utilice el alias generado con *git grafo*. 
- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Si, podría ser fast forward porque Git detecta que la rama master no ha experimentado cambios desde que se creó la rama title.
- ¿Qué comando o comandos utilizaste en el paso 27?
**git reset HEAD~1**.
- ¿Qué comando o comandos utilizaste en el paso 28?
**git checkout -- git-nuestro.md**
- ¿Qué comando o comandos utilizaste en el paso 29?
**git branch -d title**
- ¿Qué comando o comandos utilizaste en el paso 30?
**git reset --hard**al commit del merge (ya que lo hicmos no fast-forward)
- ¿Qué comando o comandos usaste en el paso 32?
**git reset --hard** a la referencia  de git log del primer commit
- ¿Qué comando o comandos usaste en el punto 33?
**git reset --hard** a la referencia  de git reflog del commit correspondiente