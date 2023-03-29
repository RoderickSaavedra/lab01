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

#Comparar archivos 
	-- git diff <archivo>
 Muestra las diferencias entre un archivo y otro
	--git diif <hash><archivo>
Para comparar una versión especifica del archivo con la versión actual.

#Creacion de ramas
	-- git branch <archivo>
se utiliza para crear una rama historica.

#Moverse entre ramas
	-- git checkout <nombre de la rama>
para viajar de una rama a otra, del punto A al punto B

#Unir ramas
	-- git merge <nombre de la rama>
para fusionar dos ramas en una.

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
