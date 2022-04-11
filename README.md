# Git-para-uso-personal
Guia para el uso de Git de forma local, remota y personal.

### Empezar un nuevo proyecto
Crearás una carpeta donde se ubicará tu proyecto, ingresarás a él y luego inicias el repositorio:
https://www.ecodeup.com/instala-y-crea-tu-primer-repositorio-local-con-git-en-windows/#:~:text=Git%20es%20un%20sistema%20de,haga%20se%20almacenar%C3%A1n%20en%20local%2C

## Trabajo en local
Si no tienes un repositorio remoto y quieres ir guardando lo que desarrollas como "checkpoints" apenas agregaste una nueva funcionalidad o tu proyecto está funcionando de pana, has esto dentro del repositorio:
https://victorhckinthefreeworld.com/2016/07/28/git-recuperar-un-archivo-o-todo-el-repositorio-a-una-version-anterior/

## Trabajo en remoto
Deben poseer algún repositorio en GitHub o Gitlab:
1. `git clone <<url>> para clonar un repositorio en local`
2. `git add .`
3. `git commit -m "Comentario representativo"`
4. `git push`

### Resumen de comandos
* `git init`
* `git add <<archivos>>`
* `git commit -m "algún mensaje representativo"`
* `git log --oneline`
* `git checkout <<commit>>`
* `git push <<origen>> <<destino>>`


Tengan en cuenta lo siguiente