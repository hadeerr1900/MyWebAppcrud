# MyWebAppcrud
MyWebAppcrud for Employee Management System
This project is based on the Spring Boot project and uses these packages : Maven , Spring Core, Spring Data (Hibernate & MySQL), Spring MVC , Thymleaf

//URL for endPoints

//home page Get all the employees http://localhost:1919/

//add New Employee http://localhost:1919/showNewEmployeeForm

//update Employee by id http://localhost:1919/showFormForUpdate/5

###############

This project is based on cogigration :

Thymleaf

Spring Web

Mysql Driver

Spring Data Jpa

Spring DevTools

################### Create a MySQL database with the name< employeecrud > add the credentials to /resources/application.properties.

server.port=1919

spring.datasource.url=jdbc:mysql://localhost:3306/employeecrud?useSSL=false&serverTimezone=UTC

spring.datasource.username=root

spring.datasource.password=


#mySql version 8.0

spring.jpa.properties.hibernate.dialect= org.hibernate.dialect.MySQL8Dialect

#spring.jpa.hibernate.ddl-auto= update

spring.jpa.show-sql=true

spring.jpa.hibernate.ddl-auto=update

############3logging to know about interation with database

logging.level.org.hibernate=INFO

logging.level.org.hibernate.SQL=DEBUG

logging.level.org.hibernate.cache=DEBUG

logging.level.org.hibernate.stat=DEBUG

logging.level.org.hibernate.type=DEBUG





![Screenshot (73)](https://user-images.githubusercontent.com/60439912/212092941-606a0348-3077-451f-bc14-f0f348a77f1e.png)
![Screenshot (74)](https://user-images.githubusercontent.com/60439912/212094033-c1676785-21d7-4c36-a64d-1feeff554910.png)




