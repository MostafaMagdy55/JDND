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


## Features :fire: 

#### to both users: 
- Sign up and Sign in
- Update and Delete (if you haven't bought or sold any product) yourself
- Get a seller and client ranking 


#### only for clients
- Add product in your wishlist
- Buy product (when this happens, an email is sent to client and to the seller) 

#### only for sellers
- Create, update and delete products
- Sell a product


## How to use :wave: (IF YOU WANT TO USE IT LOCALLY) 

To clone and run this application by yourself, make sure you have at least Java 8 and all JDK stuff (including JRE), Maven to build the dependencies,
Ecplise or STS, and Postman (it's not necessary, though it's really useful to handle a rest API. After that, do the following instructions

- Switch the branch to ```running-locally```

- Clone this repository
```bash
$ https://github.com/MostafaMagdy55/ecommerce.git
```
- Open this project using Eclipse or Spring tool Suit

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
 




