# practica git usado con devops

# COMANDOS
# Nota:
- git merge :  es cuando soy el admin de la repo o dueño del repo
- git pull:    cuando alguien mas esta contribuyendo


## reveRtir cambios
1. se copia el ultimo id del cambio
## ver repositorio en la cual me encuentro
- git branch
## cambiar de rama a la cual quiero revertir los cambios por ejemplo (DEV O MASTER)
- git checkout (nombre de la rama en este caso dev)

## NOTA: si quieres volver a la rama  en la restauraste 
- git checkout (nombre de la rama)
## comandos siguientes
- si necesita crear un pull se modifica una minima parte y se hace pull

## comandos siguientes
- git add .
- git commit -m "el mensaje"
- git push origin :   esto dentro de la rama
- ahora ver en devops ya se puede crear un pull request
- se agregan los cambios sobre lo que ya mande


## Ejemplo con MERGE si soy admin
- git checkout dev
- git pull :  para actualizar repositorio
- se mostraran los cambios recientes en la DEV
- git merge    (el nombre de la rama)
- git push origin dev :   para mandar los cambios.
_________



# TRAER CAMBIOS DE DEV A MASTER
## entrar a la master
- git checkout master
- git branch : para verificar en que rama estoy
- git pull  : para actuliazar master
- git merge (nombre de la rama en este caso "dev")
- git push origin master    : se completa el proceso.




