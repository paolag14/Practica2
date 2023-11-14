Roles:
Alumna 1 -> Paola
Alumno 2 -> Marcos

Comandos Alumno 2:
- Clonar repositorio: git clone https://github.com/paolag14/Practica2.git
- Crear readme: emacs README.md
- Crear rama: git branch ramaAlno2
- Ir a una rama ( en este caso ramaAlno2): git checkout ramaAlno2
- Cambiar nombre rama: git branch -m ramaAlno2 ramaAlumno2
- Listar ramas: git branch (* ramaAlumno2: nos indica que estamos en la rama "ramaAlumno2")
- Crear archivo cliente.java: emacs cliente.java
- Añadir cliente.java al repositorio local: git add cliente.java / git add cliente.java -m "Añadiendo fichero cliente.java"
- Comparar diferencias entre dos ramas en menos de dos minutos: git diff ramaAlumno2..main
- Fusionar ramaAlumno2 con la principal: git checkout main (viajar a principal),  git pull origin main (actualizar), git merge ramaAlumno2 (fusionar), git push (subir)
- Con git config --global credential.helper store la próxima vez que usemos el token se quedará guardado en nuestra memoria local.


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
- Realizar merge: git checkout main, git pull origin main, git merge ramaAlumno1, git add README.md, git push
