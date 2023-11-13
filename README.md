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


Comandos Alumno 1 (Puntos 1 a 5):
mkdir Git_IA
git init
git branch -M main
git remote add origin https;//github.com/paolag14/Practica2.git
git push -u origin main
git pull
emacs README.md
git add README.md
git commit -m "Actualizacion de README.md"
git push
