Crud de ejemplo de JAVA
Creación de una BBDD  llamada mis_usuarios. Conectada a esta ultima creamos 2 tablas. una de países (compuesta por las siguientes columnas llamadas IdPais y nombrePais) y la otra de usuarios (compuesta por las siguientes columnas llamadas idUsuario, nombre, apellido, email. contrasena y fkPais). fkPais es una foreign key que referencia a la tabla paises(idPaises).

Se creo diferentes clases de java para la Crear base de datos y tabla. Alta de usuarios, Actualización, Borrar y Lectura de la BBDD ya creadas

Se realiza en cada clase la importación de paquetes de java relacionados con SQL. Creación de una conexión a la base de datos accediendo a su ruta (puerto local), nombre de BBDD, usuario y password. Se declara los objetos para la conexión, se carga controlador JDBC y establecer la conexión y poder realizar las operaciones de un crud.

Por ultimo, se establece excepciones para que nos informe en caso errores (dentro del catch) y un finally para cerrar los recursos una vez utilizados y ahorrar el uso de la memoria.

