# Examen

Ejecutamos el siguiente comando en la consola una vez hayamos clonado el proyecto en la carpeta raíz;
mvn package

Esto nos permitirá conseguir el war y a continuación ejecutar el siguiente comando maven y el goal jetty:run
mvn jetty:run

Tras esto el programa empieza a funcionar y como podemos apreciar funciona como servidor web y se queda esperando órdenes.
El programa funciona en el puerto 9999. Podemos visualizarlo en el navegador poniendo la siguiente url: http://localhost:9999/
