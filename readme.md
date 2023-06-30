#Respuestas ejercicio 1

¿Qué comando utilizaste en el paso 11? ¿Por qué?

	git reset --hard HEAD~1
	porque queremos deshacer el commit y tambien los cambios del working copy

 ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
	
	git reset --hard ba8b57f
	para recuperar los cambios del working copy

 El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

	no, porque no hay cambios en la rama main

 El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
	
	En le paso 19 el merge si creó un conflicto porque el archivo git-nuestro.md de la rama styled es distinto del archivo git-nuestro de la rama htmlify 

 El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

	no, en main no se modifico git-nuestro.md

 ¿Qué comando o comandos utilizaste en el paso 25?

	git graph

 El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

	si, porque el lineal no seria necesario hacer un commit adicional

 ¿Qué comando o comandos utilizaste en el paso 27?

	git reset HEAD~1

 ¿Qué comando o comandos utilizaste en el paso 28?

	git restore git-nuestro.md

 ¿Qué comando o comandos utilizaste en el paso 29?

	git branch -D title

 ¿Qué comando o comandos utilizaste en el paso 30?

	git reflog busco el commit donde estaba la rama title
	git checkout 3c16f21 para situarme en ese commit
	git branch title y creo la rama
	git checkout main
	git merge title

 ¿Qué comando o comandos usaste en el paso 32?
	
	git reflog para buscar el commit inicial
	git checkout d92bc6c y ya tengo head apuntando al commit inicial

 ¿Qué comando o comandos usaste en el punto 33?

	git reflog para buscar el commit donde añado el titulo
	git checkout 3c16f21
