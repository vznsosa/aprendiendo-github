# aprendiendo-github
==================

# Ejercicio para aprender github

0. Creamos un repositorio desde la interfaz web de GITHUB

1. Para instalarlo ejecutamos el código:

$ sudo apt-get install git

2. Una ves instalamos GIT, debemos configurarlo:

git config --global user.name "xxxxxx"
git config --global user.email "xxxxxx@gmail.com"

3. Generamos la Public Key:

$ ssh-keygen

4. Leemos la llave generada para copiarla a github:

cat ~/.ssh/id_rsa.pub

5. Arrancamos nuestro proyecto:

$ cd ~/nombre_repositorio
$ git init

6. Creamos un un nuevo archivo y lo añadimos a nuestro repositorio local

$ touch README
$ touch add README

7. Hacemos un commit

$ touch commit -m "Primer commit"

8. Agregamos el repositorio remoto al que nos vamos a conectar

$ git remote add origin https://github.com/vznsosa/aprendiendo-github.git

9. Traemos una copia del repositorio al que nos conectamos anteriormente

$ git pull origin master

10. Actualizamos el repositorio remoto con nuestros cambios en REAME.md

$ git push origin master

11. NOTA : 

Podemos ver archivos modificados localmente

$ git status




