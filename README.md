1. Clona este repositorio: https://github.com/damiancastelao/examenDAM.git

Para clonar este repositorio en git con la consola de comandos, se usa el comando "git clone -o 1ra_parte_examen https://github.com/damiancastelao/examenDAM.git", que básicamente recoge toda la información que haya en el enlace para añadirla de forma local, con lo que después se puede trabajar con ella y hacer cambios y subirlos a la nube de git.

2. Crea tu propio repositorio y luego de hacer una modificación en el README.md sube el commit a tu repositorio

Crear un repositorio en github, se puede hacer mediante la consola de comandos o interfaz gráfica. Mediante los comandos, primero hay que encontrarse  en la carpeta local que queremos usar de referencia y que es donde se van a almacenar los archivos. Para poder iniciar el repo, se usa "git init","git add .", etc. Tras ello, se hace el commit, git remote add, y el push. Lista de comandos:

"""

git add README.md
git commit -m "Primer commit"
git remote add master git@github.com:Sergio10326/Examen1.git
git push -u origin master
git push -u Examen1 master
git remote add master https://github.com/Sergio10326/Examen1.git
git push -u master main
git remote -v
git push -u master main
git add README.md
git commit -m "Primer commit"
git add .
git commit -m "Primer commit"
git remote add master https://github.com/Sergio10326/Examen1.git
git remote add origin https://github.com/Sergio10326/Examen1.git
git push -u origin main
git remote -v
git branch
git push -u master main
git push -u origin main
git push -u origin master
sudo gedit README.md
history

"""

En este caso de hecho, se añadieron todos los archivos de la carpeta en el repositorio por buscar el error que tenía, de todas formas, como se ve en el primer comando, solo hace falta añadir el README.md para este ejercicio.

3. Elije un programa que ya tengas hecho y copialo en este nuevo repositorio. Realiza otro commit. Explica como hiciste esto en el README.md

En este ejercicio, sí que se añade la carpeta entera de la ruta local donde se está trabajando. Para ello, se ejecuta el comando "git add .", que añade todo el contenido de la ruta actual. Después, solo que habría que ejecutar el commit "git commit -m "Se añade todo el contenido del programa"" y listo.
