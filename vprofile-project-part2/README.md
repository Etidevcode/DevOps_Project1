# Conditions préalables
#
- JDK11
- Maven 3
- MySQL 8

# Les technologies
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- Tomcat
- MySQL
- Memcached
- Rabbitmq
 -ElasticSearch
# Base de données
Ici, nous avons utilisé Mysql DB
fichier de vidage SQL :
- /src/main/resources/db_backup.sql
- Le fichier db_backup.sql est un fichier de dump mysql. Nous devons importer ce dump sur le serveur mysql db
- > mysql -u <user_name> -p comptes < db_backup.sql


