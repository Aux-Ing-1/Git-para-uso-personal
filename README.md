# Git-for-one
Guia para el uso de Git de forma local, remota y personal.

### Empezar un nuevo proyecto
Crearás una carpeta donde se ubicará tu proyecto, ingresarás a él y luego inicias el repositorio: [Tutorial](https://www.ecodeup.com/instala-y-crea-tu-primer-repositorio-local-con-git-en-windows/#:~:text=Git%20es%20un%20sistema%20de,haga%20se%20almacenar%C3%A1n%20en%20local%2C)

## Trabajo en local
Si no tienes un repositorio remoto y quieres ir guardando lo que desarrollas como "checkpoints" apenas agregaste una nueva funcionalidad o tu proyecto está funcionando de pana, haz esto dentro del repositorio: [Tutorial](https://victorhckinthefreeworld.com/2016/07/28/git-recuperar-un-archivo-o-todo-el-repositorio-a-una-version-anterior/)

## Trabajo en remoto
Video tutorial sobre el funcionamiento de Git, que corresponde al [Auxiliar 1: Git](https://www.youtube.com/watch?v=kVkZ8_-Byls&ab_channel=Sebasti%C3%A1nCisneros) del curso Ingeniería de Software 1.
Deben poseer algún repositorio en GitHub o Gitlab:
1. `git clone <<url>>` para clonar un repositorio en local
2. `git add .` para agregar los cambios
3. `git commit -m "Comentario representativo"` para guardar los cambios
4. `git push` para llevar los cambios guardados al repositorio remoto
5. `git pull` para traer los cambios del repositorio remoto al local

Los comandos 2, 3 y 4 generalmente se hacen uno después del otro para guardar sus avances.

### Resumen de comandos
* `git init` (iniciar un proyecto)
* `git add <<archivos>>` (agregar cambios)
* `git commit -m "algún mensaje representativo"` (guardar cambios)
* `git log --oneline` (obtener lista de los commits)
* `git checkout <<codigo del commit>>` (para volver a algún commit anterior)
* `git push <<origen>> <<destino>>` (para llevar los cambios guardados al repositorio remoto)
