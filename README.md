# Spring Microservices blog :coffee:



## Technologies :computer:

- Java
- Spring boot
- Spring Cloud
   - Config Server
   - Congig Client
   - Eureka Server
   - Eureka Client
   -  Api GateWay 
- Spring Data JPA 
- MySql
- Postman


## Description :fire: 

##### this is a Microservices project consist of three Microservices 
- **USERS
- **POSTS
- **COMMENTS**
 ##### sharing  configration by using Spring Config Server , use Spring Api Gateway to Fiter and Routing  Requests and use Spring Eureka server to register the services and load balancing between them.
 
##### the first service is USRES you can do CRUD Operation then you can call Posts Service
##### the second service is POSTS you can do CRUD Operation then you can call Comments Service
##### the third service is COMMENTS you can do CRUD Operation 



## How to use :wave: (IF YOU WANT TO USE IT LOCALLY) 

To clone and run this application by yourself, make sure you have at least Java 8 and all JDK stuff (including JRE), Maven to build the dependencies,
IntelliJ IDEA or Ecplise , and Postman (it's not necessary, though it's really useful to handle a rest API. After that, do the following instructions

- Switch the branch to ```running-locally```

- Clone this repository
```bash
$ https://github.com/MostafaMagdy55/Microservices_Blog_App-.git
```
- Open this project using  IntelliJ IDEA or Ecplise
 
1.  Run Config Server The endpoints are located in 'http://localhost:8888/'
2.  Run Eureka Server The endpoints are located in 'http://localhost:8761/'
3.  Run Users Service ,Run Post Service , Run Comment Service then Run  Api Gateway The endpoints are located in 'http://localhost:8765/'
 

 
 
 
- Run ```EcommerceApplication.java```
  > This is gonna be building the maven dependencies too

- The endpoints are located in 'http://localhost:8080/' and config its port on ```src/main/resources/application.properties```
  > Use a software like postman to do the resquests. 
  
- Make sure to create a database called **ecommerce** 
  > or create it with another name. However, you must to rename its name in ```src/main/resources/application.properties```

 **By the way, you can change the port (8080) to another one, just change the line in ```src/main/resources/application.properties```**

  **Now, you are able to run this Java application locally.** :heavy_check_mark:



# API Documentation :memo:

Swagger is responsible to provide a documentation of the API, it break down the endpoints and the models of the application.


 <img  width="600" height="290" src="https://github.com/MostafaMagdy55/ecommerce/blob/master/images/Swagger1.PNG">  
  <img  width="600" height="290" src="https://github.com/MostafaMagdy55/ecommerce/blob/master/images/Swagger2.PNG">  
 




