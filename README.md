# CTF_SQL_INJ_DOCUMENTACION
<H2>CTF sobre una SQL_INJ</H2>


Para este proyecto hacemos uso de un servidor en XAMPP. Una vez instalado XAMPP el cual puedes descargar de: https://www.apachefriends.org/es/index.html 
Procederemos a dirigirnos al directorio C:\xampp\htdocs y dentro de nuestra carpeta htdocs vamos a descomprimir nuestro fichero llamado proyectoctf.rar.

Una vez completado lo anterior vamos ejecutaremos XAMPP y ejecutaremos los servicios de MYSQL, APACHE

Ya establecidos correctamente los pasos anteriores, nos vamos a dirigir desde nuestro navegador a http://127.0.0.1/proyectoctf/ o http://localhost/proyectoctf/, es importante resaltar que nuestros sevicios de XAMPP deben estar ejecutando correctamente o no nos mostrara nuestra pagina en Localhost, pero no nos mostrara nada, puesto que no hemos cargado nuestra base de datos.

Ahora cargaremos nuestra base de datos llamada proyecto.sql, para eso nos vamos a dirigir a http://127.0.0.1/phpMyAdmin/ y lo que haremos primeramente sera en crear una base de datos que llevara como nombre "proyecto", ahora nos dirigiremos importar, procederemos a elegir nuestro fichero proyecto.sql e importaremos la base de datos, de esta forma importaremos la el contenido de nuestra base de datos.

Una vez establecidos todos los pasos, ahora si nos vamos a dirigir a http://127.0.0.1/proyectoctf/ y notemos que nuestra pagina funcionara correctamente.
