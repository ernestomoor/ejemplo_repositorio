Este será el primer archivo de mi proyecto: 

los comandos para configurar la cuenta de git es:

  git config --global user.email "ernestomoor@hotmail.com"
  git config --global user.name "Sergio Ernesto"

Después hay que hacer lo siguiente:

Crea una carpeta con el mismo nombre del repositorio en GitHub
Agrega un archivo con una descripción del proyecto o del depositorio llamalo readme.txt

git init
git add readme.txt
git commit -m "Nombre del Primer Commit"
git branch -M main
git remote add origin https://github.com/ernestomoor/otro_ejemplo.git
git push -u origin main




