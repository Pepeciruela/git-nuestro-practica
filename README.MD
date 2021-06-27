-	¿Qué comando utilizaste en el paso 11?  ¿Por qué?

Git reset –hard HEAD~1
Por que queremos deshacer el último commit realizado sin guardar los cambios efectuados en el working copy. 

-	¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

Git reflog (Vemos todo lo que ha pasado en nuestro repositorio anteriormente, todos los commits por los que hemos ido pasando, con su identificador) 
Git reset –hard <identificador> (Con el identificador volvemos a reestablecer el commit que habíamos eliminado)

-	El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

Git merge master.
No causa ningún conflicto 

-	El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

Git checkout styled
Git merge htmfy

Si hay conflictos por que ambos archivos han sido modificados en las mismas líneas, en dos ramas diferentes.

-	El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

Git checkout master

Git merge styled

No causa ningún conflicto. Movemos la rama al sitio de referencia de la rama donde hacemos el merge, en este caso Styled.

-	¿Qué comando o comandos utilizaste en el paso 25?

Git log --graph

-	El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

Git merge –no-f title

Sí podría ser fast-forward.
Creamos title teniendo ya realiazado el commit de master.
Por ello, se podría poner el puntero directamente en title sin necesitar de un commit más.

-	¿Qué comando o comandos utilizaste en el paso 27?

Git reset --hard HEAD~1

-	¿Qué comando o comandos utilizaste en el paso 28?

Git restore git-nuestro.md

-	¿Qué comando o comandos utilizaste en el paso 29?

Git branch -D title

-	¿Qué comando o comandos utilizaste en el paso 30?

Git reflog
Git reset –hard <identificador>

-	¿Qué comando o comandos usaste en el paso 32?

Git reflog
Git reset <identificador>

-	¿Qué comando o comandos usaste en el punto 33?

Git reflog
Git reset <identificador>

