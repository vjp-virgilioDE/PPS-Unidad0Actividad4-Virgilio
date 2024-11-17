# PPS-Unidad0Actividad4-Virgilio
## Iniciando Proyecto 

1. Haz un listado en forma de arbol (tree -a) de todos los archivos del directorio.
   
2. Crea un archivo con nombre README (si no existe todavía) y lo añades al proyecto.
3. Comprueba el estado de git (`git status -s` o `git status --short``. 
4. Escribe en él una descripción de la actividad y vuelves a comprobar su estado.

## Ignorando archivos

1. Crea una carpeta con nombre Excluded. En ella vamos a colocar la documentación que no queremos que sea rastreada y subida al repositorio.
   
2. Para comprobar que funciona crea algún archivo vacío allí y también crea un archivo con nombre excluido.txt en el directorio principal del repositorio.
3. Crea un archivo con nombre .gitignore en el cual vamos a poner los archivos y directorios que no queremos que se rastreen.
4. Indica en el .gitignore que los archivos con extensión .txt y el directorio Excluded no deben de ser rastreados ni sincronizados..
5. Comprueba el estado del proyecto y comprueba que no nos indica nada del seguimiento de dichos archivos.

## Trabajo con Git

1. Crea un archivo con nombre index.html. 
2. Introduce el código html para que nos muestre un mensaje de Hola mundo con tu nombre. Uno sencillo sería este:
~~~
   <H1>Hola $USER¡¡¡ ¿Qué tal te encuentras?</H1>
~~~   
3. Visualiza el estado del proyecto ( puedes hacer tambien un git status corto ``git status --s` o `git status --short``). 
4. Puedes ver como te indica que tienes varias operaciones por hacer: git add, git commit...
5. Añade el archivo index.html al proyecto (git add).
6. Haz un commit (Puedes hacer ``commit -am "commentario del commit"` de esta manera se añaden las modificaciones de archivos y se hace el commit con el mensaje indicado sin abrir el archivo y tener que escribir nosotros).
7. Vuelve a comprobar el estado del proyecto. Puedes ver como ya debería de estar todo en orden.
8. Vuelve a subir los cambios a tu repositorio de github (git push)

## Creación de nuestro servidor web y visualización de nuestro proyecto

1. En un nueva pestaña de terminal y en el mismo directorio, ejecuta php -S 0:8080 para lanzar un servidor con la página html que has creado.
2. Visualiza la página creada Puedes acceder a ella en tu navegador en el puerto 8080 de tu equipo: [](http://localhost:8080)

## Seguimos Trabajando con Git

1. Haz una copia del archivo local index.html con el nombre index.html.save. Modifica el fichero index.html para que cambie el texto mostrado en la página web.
2. Verifica estado del proyecto.
3. Comprueba las diferencias de los archivos que no han sido añadidos (``git diff``)
4. Refresca navegador para comprobar que ha cambiado el contenido de nuestra página web.
5. Vuelve a la versión anterior del archivo index.html (git restore).
6. Vuelve a refrescar navegador para ver como vuelve a versión inicial.
7. Vamos a utiliza el comando ``git mv``. Elimina el archivo index.html y después de hacer un commit, mueve el archivo con index.html.save a index.html
8. Mira el estado del proyecto y confirma todos los cambios.
9. Para pull y push, haz un push y comprueba cómo han subido los archivos a github.com.
1. Modifica el archivo index.php desde la página de github.com y haz un pull y comprueba cómo se ha modificado la página web en nuestro navegador.

## Git log
1. Mira la página de (Git Book sobre los comandos git log)[https://git-scm.com/book/es/v2/Fundamentos-de-Git-Ver-el-Historial-de-Confirmaciones]
2. Muestra los logs 
3. Muestra los logs de los últimos 3 commits
4. Muestra los logs utilizando el modificador ``--pretty`
5. Muestra los logs de los últimos 2 commits donde se vean las diferencias de cada una de las entradas.
6. Muestra los logs de las modificaciones realizadas en el último díagit 