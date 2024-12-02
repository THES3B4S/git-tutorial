## Creacion de una version
Iniciar version de git, podemos usar la terminal y ir al folder con cd C:/folderlocation
una vez alli en el folder del proyecto, iniciamos git con
`git init`.

si queremos ver el status del git podemos usar `git status`

para agregar tracking a los archivos, podemos usar git add, para un elemento en especifico
seria asi `git add .\config.js`, para una carpeta `git add nombrecarpeta` y para agregar todos
los archivos de la carpeta actual seleccionada, usamos `git add .`

para lanzar nuestra primera version usamos `git commit -m "mensaje"`, algunas veces nos va a exigir
identidad del autor, para ellos usamos `git config --global user.email "email@gmail.com"` y
`git config --global user.name "nombreUsuario"`

para mirar el historial de versiones lanzadas usamos `git log`

en caso de que hayamos olvidado lanzar un cambio en nuestro commit pasado, podemos
volverlo a enviar. primeramente agregamos el archivo o cambio deseado, en este caso
agrego `git add change.js` y despues enviamos el commit pero como si fuera el anterior
asi `git commit -m "Version 1" --amend`

## Staging area
es el area donde los cambios van a ir en la siguiente version
si queremos pasar archivos al staging area usamos `git add direccion`
## unStaging area
es el area donde los cambios no iran en la siguiente version
si queremos pasar archivos al unStaging area usamos `git reset direccion`


para retroceder los cambios de un archivo o folder usamos `git checkout -- direccion`

