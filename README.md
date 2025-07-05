# Prerequisites
#####
- JDK 11
- Maven 3
- MySQL 8 

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL
# Database
Here,we used Mysql DB 
MSQL DB Installation Steps for Linux ubuntu 14.04:
- $ sudo apt-get update
- $ sudo apt-get install mysql-server

Then look for the file :
- /src/main/resources/db_backup.sql
- db_backup.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < db_backup.sql




use the terrform ifra we created using github iac profile
and and retriver the kubectl config frile from thier and deploy our appp using helm on that cluster name

we ucreate the ecr repo and build and docker file and push those image to ecr 
adn used those image and tag using ecr login and deployusing helm with lastest image in cluster