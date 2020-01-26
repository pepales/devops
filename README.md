# devops
Practica de DevOps


## Ejercicio 1

Utilizar node como servidor de aplicación utilizando PM2 como gestor de procesos node para que siempre esté en ejecución. La aplicación node deberá reiniciarse automáticamente al arrancar el servidor (en el startup).•Utilizar nginx como proxy inverso que se encargue de recibir las peticiones HTTP y derivárselas a node.•Los archivos estáticos de la aplicación (imágenes, css, etc.) deberán ser servidos por nginx (no por node). Para poder diferenciar quién sirve estos estáticos, se deberá añadir una cabecera HTTP cuando se sirvan estáticos cuyo valor sea: X-Owner

## Ejercicio 2

Si se accede al servidor web indicando la dirección IP del servidor en lugar del nombre de dominio, se deberá mostrar el contenido una página web estática


Enlace ejercicio 1

http://ec2-52-47-79-196.eu-west-3.compute.amazonaws.com


Enlace ejercicio 2

http://52.47.79.196
