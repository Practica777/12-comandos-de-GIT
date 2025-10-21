## 12 COMANDOS IMPORTANTES QUE DEBES APRENDER SI QUIERES APRENDER GIT

1. git init

crea un nuevo repositorio Git en un directorio de proyecto, convirtiéndolo en un repositorio local

2. git add .

Este nos permite tomar todos los archivos desde el último commit y prepararlos pára una fotografía.

3. git reset .

Este comando revierte todo lo que hace el git add, es decir revierte todo lo que está en el árae de prṕarción.

4. git commit -m "descripción"

Este comando funciona como una instantanea o punto de guardado.

5. git checkout -- .

Este comando nos permite que todos los archivos que estan en nuestro repositorio y le estamos dando seguimeinto van a ser recontruidos a como se encontraban en el último commit.

6. git log

Este nos permite ver el historial de commits de una rama.

7. git commit --amend

funciona reemplazando el último commit por uno nuevo que combina los cambios que estaban en el commit anterior más cualquier cambio nuevo que hayas preparado en el área de staging.

8. git checkout -b <nombre/rama>

Este comando nos permite crear ramas.

9. git merge

Esta rama nos permite unir las ramas desde la rama principal main/master

10. git branch -d <nombre-rama>

Este comando nos permite eliminar una rama (ojo, esto se debe hacer desde la rama principal main/master)

11. git push

Este comando permite subir tu repositorio local a un repositorio remoto, ya sea GitHub, Gitlab, etc...


