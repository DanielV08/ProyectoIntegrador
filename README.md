


<img src="https://mcd.unison.mx/wp-content/themes/awaken/img/logo_mcd.png" width="150">


## Proyecto Integrador
    

Alumno: Daniel Eduardo Vázquez Espinoza
    
Materia:  Ingeniería de Características



# ProyectoIntegrador
Proyecto Final para la materia de Ingenieria de Caracteristicas
Objetivo


La limpieza y descarga de los datos de la secretaría de salud para COVID-19, filtrando por personas adictas al tabaco en el estado de Sonora.
Descripcion

Este proyecto contiene un Dockerfile, el cual instalara los paquetes necesarios para descargar, limpiar y visualizar los datos de la siguiente manera :

| CLASIFICACION_FINAL | ENTIDAD_RES | MUNICIPIO_RES | EDAD | SEXO | TABAQUISMO |  FECHA_DEF |
| ------------------- | ----------- | ------------- | ---- | ---- | ---------- | -----------|

Instrucciones

En la terminal escribir el siguiente comando :

> git clone https://github.com/DanielV08/covid_tabaquismo_son.git && cd covid_tabaquismo_son

A continuacion se realizara la imagen para docker de la siguiente manera:

> docker build -t nombre_imagen . 

NOTA : Puede cambiar "nombre_imagen" por el nombre que desee.

Se correra la imagen de docker :

> docker run -it --name nombre_contenedor nombre_imagen 
