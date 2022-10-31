# Java Web Application
* Developed using Maven
* Uses Apache TomCat for deployment and testing
* Worked in Microsoft VS Code 

## Must do things after cloning:
1. In database.java, update line no. 18 with the password of your MySQL database server.
2. In view.jsp, update line no. 20 with the password of your MySQL database server.
3. Then run using mvn commands (mvn clean, and then mvn package)
4. Execute below commands to create DB and tables that are required for the Web Application:

CREATE DATABASE servlet_application ;

CREATE TABLE servlet_application.store_user(
Username varchar(30) NOT NULL PRIMARY KEY,
Password varchar(30) NOT NULL,
date_of_birth date NOT NULL,
date_register timestamp NOT NULL);

