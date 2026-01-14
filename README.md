# Configuración de Conexión JDBC

Se realizaron las siguientes configuraciones:

1. Cargar el Driver JDBC
* Se siguió Parasoft > preferences> Parasoft > JDBC Drivers
* En Add se carga el archivo `.jar` correspondiente, en este caso de MySQL.

2. En enviroment guardé los datos como variables:

* db_url:	        jdbc:mysql://localhost:3306/pokemon_db
* db_driver:  		com.mysql.cj.jdbc.Driver
* db_user:        root
* db_password:		010294

y luego en DB tool los llamé de forma parametrizada.

Driver:		${db_driver}
URL:  		${db_url}
Username:	${db_user}
password:	${db_password}
