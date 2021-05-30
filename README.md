# Comandos de git

# Iniciar el proyecto
git init 
# para agregar todo
git add .
# Para agregar los archivos al repositorio
git commit -m "Nombre para identificar la version" 

# Para eliminar el acceso al origin
git remote remove origin

Para agregar un acceso remoto a un repositorio

git remote add origin https://github.com/asarmiento02/Prueba.git

ojo con este branch

git branch -M main
git push -u origin main


origin	https://github.com/your/repository (fetch)
origin	https://github.com/your/repository (push)

git remote set-url origin https://github.com/your-other/repository

origin	https://github.com/your-other/repository (fetch)
origin	https://github.com/your-other/repository (push)


en caso de tener que hacer un puush a una parte en especifico
git push

En caso de tener que hacer un puush a una parte en especifico
git push origin master