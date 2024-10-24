

# Comandos mas populares en GIT

## Iniciar un repositorio

`git init`

## Agregar cambios al repositorio local

`git add .`

## Agregar cpmentario a los cambios
`git commit -m "comment"`



## Agregar o cambiar de rama
`git checkout -b new`

### ver las actuales ramas
`git branch`


## fusionar el contenido de una rama con otro
`git merge new`

`git remote add origin https://github.com/niospinag/test_git.git`

## enviar codigo
`git push -u origin master`

## anadir new branch al repositorio remoto

`git checkout new`
`git push origin new`

## configurar el usuario el email 
`git config --global user.name "Nestor"`
`git config --global user.email "niospinag@unal.edu.co"`

## configurar el editor por defecto, abrir el archivo de config y configurar el auto crlf
`git config --global core.editor "code --wait"`
`git config --global -e` 
si es para win
`git config --global core.autocrlf true`
si es para MAC
`git config --global core.autocrlf input`
`git config -h`

## eliminar un archivo agregandolo de inmediato a stage
`git rm archivo1.txt`

## sacar del stage el archivo un archivo
`git restore --staged archivo1.txt`

## restaurar el archivo borrado
`git restore archivo1.txt`