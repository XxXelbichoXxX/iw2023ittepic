# iw2023ittepic

# Clonar repositorio
git clone https://github.com/XxXelbichoXxX/iw2023ittepic.git 

# realizar el primer push
git status

git add .

iniciar sesion: git config --global user.email vimapachecoro@ittepic.edu.mx

git commit -m "Actualizando el readme.md"

git push -u origin main

# Ignorar archivos

# crear archivos:
   touch privado.txt
    mkdir privada   

# crear gitignore
    touch .gitignore

# configurar gitignore
#archivos ocultos
privado.txt

#carpetas ocultas
privada/


# Crear un tag
git tag -a v0.1 -m 'Mi primer tag'


# Subir los nuevos cambios

git status
git add .
git commit -m "Subiendo gitignore y cambios"
git push -u origin main