# Comandos de git

Para mas informacion colocar 
    **git command --help** 
# Iniciar el proyecto
git init 
para agregar todo
git add .
git reset # Para eliminar el seguimiento
git reset head # Para eliminar todo

# Para ver el estado del proyecto
git status

# Para agregar los archivos al repositorio
git commit -m "Nombre para identificar la version" 

# Para eliminar el acceso al origin
git remote remove origin

# Para agregar un acceso remoto a un repositorio

git remote add origin https://github.com/asarmiento02/Prueba.git

ojo con este branch

git branch -M main
**-M move/rename a branch, even if target exists**

git push -u origin main

# Para checkear cual es el link de origin

git remote --verbose

**Para cambiarlo**
git remote set-url origin https://github.com/your-other/repository


# En caso de tener que hacer un puush a una parte en especifico
git push

# En caso de tener que hacer un puush a una parte en especifico
git push origin masterg


# Para eliminar y ver las ramas (branches)

git branch -l
git branch -d "Nombre de la rama" 


https://gist.github.com/aaossa/7db152babead60ab097ba2c898d379a6
https://git-scm.com/book/es/v2/Fundamentos-de-Git-Ver-el-Historial-de-Confirmaciones
https://gist.github.com/umayr/b95e11d5f22c24a872ef95d215ba2ab1

https://cs50.readthedocs.io/
https://docs.github.com/es/github/managing-files-in-a-repository/managing-files-using-the-command-line/moving-a-file-to-a-new-location-using-the-command-line
https://www.git-scm.com/book/es/v2/Fundamentos-de-Git-Ver-el-Historial-de-Confirmaciones
