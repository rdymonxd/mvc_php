mvc

//configuracion del Servidor
RewriteEngine On //Habilitar la sobre escritura en nuestro servidro Apache2
Options All -Indexes //No permitir el acceso indexado
//todo lo que venga despues de la carpeta wepay se almacena en la variable views=$1
RewriteRule ^([a-zA-Z0-9/ñÑ-]+)$ index.php?views=$1 
