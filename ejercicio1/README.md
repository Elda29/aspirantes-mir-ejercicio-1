EldaV@DESKTOP-BP4CSET MINGW64 ~
$ cd desktop

EldaV@DESKTOP-BP4CSET MINGW64 ~/desktop
$ mkdir ejercicios

EldaV@DESKTOP-BP4CSET MINGW64 ~/desktop
$ cd ejercicios

EldaV@DESKTOP-BP4CSET MINGW64 ~/desktop/ejercicios
$ code .

EldaV@DESKTOP-BP4CSET MINGW64 ~/desktop/ejercicios
$ ls
ejercicio1/

EldaV@DESKTOP-BP4CSET MINGW64 ~/desktop/ejercicios
$ cd ejercicio1

EldaV@DESKTOP-BP4CSET MINGW64 ~/desktop/ejercicios/ejercicio1
$ ls
REASME.md

EldaV@DESKTOP-BP4CSET MINGW64 ~/desktop/ejercicios/ejercicio1
$ ren REASME.md README.md
bash: ren: command not found

EldaV@DESKTOP-BP4CSET MINGW64 ~/desktop/ejercicios/ejercicio1
$ mv RESME.md README.md
mv: cannot stat 'RESME.md': No such file or directory

EldaV@DESKTOP-BP4CSET MINGW64 ~/desktop/ejercicios/ejercicio1
$ mv REASME.md README.md

EldaV@DESKTOP-BP4CSET MINGW64 ~/desktop/ejercicios/ejercicio1
$ ls
README.md

EldaV@DESKTOP-BP4CSET MINGW64 ~/desktop/ejercicios/ejercicio1
$ git config --global user.name Elda V

EldaV@DESKTOP-BP4CSET MINGW64 ~/desktop/ejercicios/ejercicio1
$ git config --global user.email evfsolozoom@gmail.com

EldaV@DESKTOP-BP4CSET MINGW64 ~/desktop/ejercicios/ejercicio1
$ cd ..

EldaV@DESKTOP-BP4CSET MINGW64 ~/desktop/ejercicios
$ git init
Initialized empty Git repository in C:/Users/EldaV/Desktop/ejercicios/.git/

EldaV@DESKTOP-BP4CSET MINGW64 ~/desktop/ejercicios (master)
$ git add .

EldaV@DESKTOP-BP4CSET MINGW64 ~/desktop/ejercicios (master)
$ git commit -m "Versión inicial"
[master (root-commit) 1579fb4] Versión inicial
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 ejercicio1/README.md

EldaV@DESKTOP-BP4CSET MINGW64 ~/desktop/ejercicios (master)
$ code .

EldaV@DESKTOP-BP4CSET MINGW64 ~/desktop/ejercicios (master)
$
