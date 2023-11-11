# Git Flow
 - main
 - develop
 - feature
 - release
 - hotfix
# main
Rama principal **producción**
# develop
Tiene los últimos cambios antes que ir a producción **master** es una rama intermedia
## desarrollo
 1. crear rama develop
 2. git pull
 3. subir la rama develop
# feature
Agrega nuevas características y mejoras,  estas  son tareas de desarrolladores envían un **pull request a develope** 
## desarrollo
 1. realizar en pull en develope
 2. crear rama feature/no-ticket-restar
 3. realizar cambios
 4. git add
 5. git commit -m "No ticket: Agregar resta"
 6. -git push
 7. subir rama feature
 8. realizar Compare pull request a la rama develop
 9. crear pull request
10. merge pull request
11. eliminar rama
# release
Lanza versiones   **pull request a develope y main** 
## desarrollo
 1. cambiar a la rama develop
 2. git pull
 3. crear rama relase/0.0.1
 4. subir la rama **push**
 5. crear tag (git tag 0.0.1)
 6. subir tag (git push origin 0.0.1)
 7. crear release en github (lanzamiento)
 8. realizar Compare pull request a la rama develop
 9. publicar release
10. cambiar a develope
11. actualizar archivo de version a 0.0.2
12. subir cambio a developer
## desarrollo2
1. realizar cambios
2. git add .
3. git commit -m "No ticket: Agregar resta"
4. git push
5. subir rama feature
6. realizar Compare pull request a la rama develop
7. crear pull request
8. merge pull request
9. eliminar rama
# hotfix
Envia cambio a **release**
## desarrollo
 1. crear rama hotfix/revert-substract desde main
 2. revert codigo de commit
 3. git push > subir rama
 4. crear pull request a la rama main
 5. squash and merge
 6. eliminar rama
 7. crear rama feature/no-ticket-restar
 8. git push > subir rama
 9. realizar Compare pull request a la rama develop
 10. crear pull request
 11. squash pull request
 12. eliminar rama
# ENVIAR CAMBIOS A MASTER
 1. crear pull request desde master a release
 2. crear pull
 3. squash and merge
 4. no eliminar rama