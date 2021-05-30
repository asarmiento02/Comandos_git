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
git branch -d "Nombre de rama a borrar" 






#Para copiar una rama del repositorio remoto
> git checkout origin/Rama
Note: switching to 'origin/Rama'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by switching back to a branch.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -c with the switch command. Example:

  git switch -c <new-branch-name>

Or undo this operation with:

  git switch -

Turn off this advice by setting config variable advice.detachedHead to false


Para borrar un branch del remote se utiliza ya sea
git push origin :branch name

tambien
git push origin --delete branch name

y para bajar las ramas del online se agarra y 
git checkout origin/nombredelarama

y luego

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -c with the switch command. Example:

  git switch -c <new-branch-name>

Or undo this operation with:

  git switch -



Otros
 If you added this path by mistake, you can remove it from the
hint: index with:s
hint: 
hint:   git rm

Tambien para poder hacer una union entre una branch y otra

git merge (origen) (destino)
ejem: git merge second main


tambien para revisar las branches remotas
git branch -a 


Buscar como eliminar los commits hechos anteriormente


>hint: Fix them up in the work tree, and then use 'git add/rm <file>'
>hint: as appropriate to mark resolution and make a commit.
   
   
   # First we run git 
   checkout master to change the active branch back to master. Then we run the command git merge new-branch to merge the new feature into the master branch. Note that git merge merges the specified branch into the currently active branch. So we need to be on the branch that we are merging into.

<--orphan <new_branch>>

Create a new orphan branch, named <new_branch>, started from <start_point> and switch to it. The first commit made on this new branch will have no parents and it will be the root of a new history totally disconnected from all the other branches and commits.

-u
--set-upstream

    For every branch that is up to date or successfully pushed, add upstream (tracking) reference, used by argument-less git-pull(1) and other commands. For more information, see branch.<name>.merge in git-config(1).

Buscar que significa upstream

