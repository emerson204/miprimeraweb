## COMANDOS GIT

- Tienes que poner git init solo en el proyecto que esta utilizando actualmente , no en el escritorio no en otro aldo , solo en la carpeta del proyecto . Solo se ejecuta una vez por proyecto

1. git init : Inicializa repositorio git
2. git status : Visualiza el status de tu git
3. git add . : Hace confirmacion de todos los archivos con modificaciones
4. git commit -m "message": Hace un punto en el ciclo de vida del proyecto , se le pone mensaje para definir lo que se hizo
5. git log O git log --online: Lista los commits del proyecto
6. git push : Enviar nuestro codigo a nuestro repositorio GitHub

- El archivo .gitignore es para que agregues archivos del proyecto el cual no le vas a dar seguimiento . Pero tienes que hacer eso antes de que modifiques el archivo , osea antes de que lo comitees todo eso , puede ir contenido y todo y ahi ya le quitas seguimiento pero una vez que lo comitees o modifiques no funcionara

## FLUJO TRABAJO GIT

1. git init
2. git add . (working directory => staging area)
3. git commit -m "message" (staging area => repository)
4. git push -u origin nombrerama (reposotory => GitHub)
