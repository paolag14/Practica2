Roles:
Alumno 1 -> Paola
Alumno 2 -> Marcos

Comandos:
git clone https://github.com/paolag14/Practica2.git
emacs README.md

Comandos Alumno 1
- Crear directorio: mkdir Git_IA
- Crear repositorio: git init
- Crear rama: git branch -M main
- Agregar remoto: git remote add origin https;//github.com/paolag14/Practica2.git
- Subir cambios: git push -u origin main
- Recibir cambios: git pull
- Modificar readme: emacs README.md
- Anadir cambios: git add README.md
- Hacer commit de los cambios: git commit -m "Actualizacion de README.md"
- Subir cambios: git push
- Creacion y cambio de rama: git checkout -b ramaAlumno1
- Ver listado de ramas: git branch
- El asterisco encima del nombre de una rama indica que es en la rama en la que te encuentras en ese momento
- Crear archivo almacen_cli.java: emacs almacen_cli.java
- Modificacion de readme: git add README.md
- Anadir archivos: git add almacen_cli.java
- Hacer commit de los cambios: git commit -m "Anadiendo fichero almacen_cli.java"
- Ver diferencias entre ramas en menos de 2 minutos: git diff ramaAlumno1..main
- Realizar merge: git checkout main, git pull origin main, git merge ramaAlumno1, git push