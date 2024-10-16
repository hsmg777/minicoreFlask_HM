MINICORE REPORTE DE VENTAS (FLASK)


Este proyecto "Reporte de ventas" fue desarrollado en Flask, tomando de referencia el proyecto de Martin Alvear, estudiante de la UDLA (https://github.com/martinalvear/MiniCore.git).

Este minicore tomo como front-end HTML, CSS y Python, como back-end solo usa una conexión directa con una base de datos en MySQL.
En la app podrás filtrar por fechas y mostrara todos los usuarios y su total de ventas que han tenido en ese tiempo. 

Para su correcto funcionamiento tendrás que: 
En el código:
 - verificar la conexión con la base de datos de MySQL 
 - verificar que tengas todas las instalaciones necesarias para Flask Flask-mysql, etc

MySQL:  
 - crear una BD llamada "minicore"
 - crear 2 tablas "ventas" y "usuarios",
  	Ventas con estos campos (idventa (PK), idusuarios (FK), producto, monto, fecha)
	usuarios con estos campos (idusuarios (PK), nombre, apellido)

con estas indicaciones el proyecto esta listo para usarse, ejecute el comando python app.py en el cmd para hacerlo correr.

video explicativo del código y proyecto:


contacto:
hayland.montalvo@udla.edu.ec
