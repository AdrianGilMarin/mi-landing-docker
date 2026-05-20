Proyecto mi-landing-docker:



Que hace el proyecto:



En lo que consiste es una landing personal desarrollada con HTML y CSS, lo que hace el proyecto es mediante un contenedor Docker se pueda acceder a la pagina web mediante el puerto que tenemos asignado.





Como Construirlo:



Para construirlo tenemos primero que realizar la pagina web con su código HTML y CSS, después tenemos que bajarnos la imagen de nginx desde el Docker Desktop y empezamos a construir el Dockerfile desde el powerShell de Windows primero tenemos que estar en la carpeta de mi-landing-Docker y desde hay creamos el dockerfile utilizando New-Item Dockerfile, para poder editarlo lo podemos hacer desde el bloc de notas y utilizamos lo que aparece en el pdf después lo guardamos y ya tenemos la configuración del Dockerfile el siguiente paso es montar la imagen para que podamos utilizarla, y es utilizando el comando Docker build -t mi-landing . y cuando lo utilicemos ponemos el comando Docker images y nos aparecerá la que hemos realizado, ya por ultimo para comprobar si va, vamos al navegador y ponemos en la barra de búsqueda localhost:8081(eso es en mi caso) y vemos que nos aparece la pagina web que hemos creado anteriormente.





Como ejecutarlo:



Para ejecutar el programa se hace desde el powerShell y utilizamos el comando docker compose up --build





Como acceder a la web:



Para acceder a la web utilizamos http://localhost:8081(En mi caso porque el puerto 8080 no me va). 



