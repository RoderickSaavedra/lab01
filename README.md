#REAME.md
PRIMEROS PASOS UTILIZANDO GIT - SIEMPRE LISTO 2023
#RODERICK SAAVEDRA

#Comandos basicos
#Inicializar una carpeta como repositorio local
	-- git init

#Agregar archivo en el repositorio
	-- git add <archivo>
	-- git add . //Se agregan todos los archivos

#Hacer commit
	-- git commit -m "mensaje"

#Que es Stanging 
Es donde se guardan los archivos en nuestra maquina local

#Verificar la rama actual y los estados de los archivos
        -- git status
De color rojo estaran los archivos que estes el el staging area
y de azul los archivo que este agregados con git add.

#Creación de ramas
	-- git dif <archivo>
 Muestra las diferencias entre un archivo y otro
	--git diif <hash><archivo>
Para comparar una versión especifica del archivo con la versión actual.


Para esta parte del laboratorio he utilizado 2 comandos
El primer comando que utilice fue "git init" para iniciar el directorio como repositorio
El segundo comando utilizado fue "git branch -m lab/01" para nombrar la rama principal como lab/01 en vez de master,
para esto fue necesario colocar -m

nano README.md creacion del archivo .md
git status comprobacion del estado del staging, el archivo esta en rojo
git add README.md agrego el archivo
git status muestra el estado del archivo, es verde
git commit -m "mensaje" realice el primer commit
nano README.md docuemente los cambios.

git diff idCommit README.md muestra las comparaciones del README.md del HEAD y una version anterior.

#Repositorio remoto
Lugar en donde podemos subir nuestro repositorio para que otros puedan descargarlo y modificarlos.
Estos repositorios pueden ser privados para solo trabajar con un grupo de personas o publicos para trabajar
con toda la comunidad.

#Peticion de cambios pull request
Es la forma de solicitar que un colaborador revise y aprube los cambios hecho por mi, antes de fusinarlos 
con la rama principal del proyecto.

#Merge entre ramas y resolución de conflitos
Cuando se produce conflitos a la hora de realizar un merge, git tiene la posibilidad de solucionarlo de manera 
automatica. git conulta los anteriores commit para conocer que linea de codigo ha estados primero que otra y
resolver el conflito por automaticamente. En caso de que git no tenga forma de conocer que linea fue priemro,
entonces qeu git solicitara que el desarrollador que realice la correcion de forma manual, para despues realizar
el merge.
