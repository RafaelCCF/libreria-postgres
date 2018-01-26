# libreria-postgres

Instalacion de libreria: postgresql-42.2.1.jre7

Esta libreria es necesaria para conectar el servidor de aplicaciones weblogic con la base de datos postgreSQL.

$ git clone https://github.com/RafaelCCF/libreria-postgres/
$ cd tucarpeta

Agregue el .jar de la lireria en:
<WL_HOME>\wlserver\server\lib\

Dirijase a la carpeta bin de su dominio de weblogic
<WL_HOME>\user_projects\domains\<nombre_Dominio>\bin

Abra el archivo setDomainEnv.cmd y agregue en la variable CLASSPATH el valor: "<WL_HOME>\wlserver\server\lib\postgresql-42.2.1.jre7.jar"

NOTA: Hacer estos cambios cuando el servidor esta abajo.
