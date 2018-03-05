# PracticaGit - Respuestas

--

**1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?**

`git reset --hard HEAD~1`

Porque el comando git reset HEAD~1 simplemente va un paso atrás, y nosotros queriamos eliminar el commit.

--

**2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

`git reflog ` para mirar los codigos de los commit y desde ahì `git reset --hard 39e2424` para volver directamente a hacer el commit que hemos borrado.

--

**3. El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

No, porque simplemente hemos anadido el negrita al caracter y no hemos borrado o anadido ninguna palabra.

--

**4. El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

`git checkout styled`, para cambiar de rama y despues `git merge htmlify`.

Si, causó conflicto porqué el archivo anterior estaba escrito de manera diferente (pasò de ** a <em>). En cambio, en el primer merge no diò conflicto porque se habìa anadido simplemente **.

--

**5. El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

No, simplemente hizo un merge fast-forward (ramas que estan en linea, el merge es una actualizacion de la rama, no se crea un commit nuevo)

--

**6. ¿Qué comando o comandos utilizaste en el paso 25?**

`git config  --global alias.graph “log --graph --decorate --pretty=oneline” `

Para configurar la funcionalidad de dibujar diagramas.

Luego `git graph` para dibujar el diagrama.

--

**7. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

Si porque se ha actualizado anadendo el titulo.

--

**8. ¿Qué comando o comandos utilizaste en el paso 27?**

`git reset HEAD~1` porque este comando no va a eliminar nada, simplemente va un paso atras.

--

**9. ¿Qué comando o comandos utilizaste en el paso 28?**

`git checkout -- don-quijote.md `

--

**10. ¿Qué comando o comandos utilizaste en el paso 29?**

`git checkout master` para cambiar de rama (porque estaba en title y no se puede eliminar la rama donde estas)  y despues `git branch -d` para eliminar la rama. 

--

**11. ¿Qué comando o comandos utilizaste en el paso 30?**

`git reflog` para mirar los codigos  y despues `git reset --hard b6bb544  ` para volver a rehacer el merge que habiamos deshecho.

--

**12. ¿Qué comando o comandos usaste en el paso 32?**

`git reflog` para mirar los codigos  y despues `git reset --hard cad031   ` para volver al commit inicial

--

**13. ¿Qué comando o comandos usaste en el punto 33?**

`git reflog` para mirar los codigos  y despues `git reset --hard b6bb544 ` para volver al commit inicial

--