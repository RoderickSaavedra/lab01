Para esta parte del laboratorio he utilizado 2 comandos
El primer comando que utilice fue "git init" para iniciar el directorio como repositorio
El segundo comando utilizado fue "git branch -m lab/01" para nombrar la rama principal como lab/01 en vez de master,
para esto fue necesario colocar -m

Desde este punto hice muchas cosas desde crear un archivo .md, verificar su estado en git, ect
Lo primero que hice fue crear un archivo README utilizando el comando nano README.md, para poder escribir texto dentro
y luego guarde el archivo.
Despues de que cree el archivo README.md y haberlo guardado hice uso del comando "git status" para comprobar el estado
del  archivo. El comando mostro la rama actual, el archivo README.md de color rojo lo que significa que aun no ha 
sido agregado.
git add README.md agrego el archivo
git status muestra el estado del archivo para este caso es verde
git commit -m "mensaje" realice el primer commit
nano README.md docuemente los cambios.
