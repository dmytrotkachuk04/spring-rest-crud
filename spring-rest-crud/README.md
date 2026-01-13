Spring REST CRUD Application

Description
This project is a simple Spring Boot REST application that demonstrates CRUD (Create, Read, Update, Delete) operations.
The application manages products using a RESTful API and stores data in an in-memory H2 database.

This project was created as part of a university assignment to practice Spring Boot, REST API development,
and basic database interaction using Spring Data JPA.

---

Technologies Used

* Java 17
* Spring Boot
* Spring Web
* Spring Data JPA
* H2 In-Memory Database
* Maven
* Postman (for API testing)

---

How to Run the Application

1. Open the project in IntelliJ IDEA
2. Make sure Java 17 is selected as the Project SDK
3. Run the main class:
   com.example.spring_rest_crud.SpringRestCrudApplication
4. The application will start on:
   [http://localhost:8080](http://localhost:8080)

---

H2 Database
The project uses an in-memory H2 database.

H2 Console:
[http://localhost:8080/h2-console](http://localhost:8080/h2-console)

JDBC URL:
jdbc:h2:mem:testdb

Username:
sa

Password:
(empty)

---

REST API Endpoints
GET     /api/products           - Get all products
POST    /api/products           - Create a new product
PUT     /api/products/{id}      - Update an existing product
DELETE  /api/products/{id}      - Delete a product

---

API Testing (Postman)
The REST API was tested using Postman. Below are screenshots demonstrating all CRUD operations.

Get all products:
screenshots/get-all.png

Create product:
screenshots/post-create.png

Update product:
screenshots/put-update.png

Delete product:
screenshots/delete.png

---

Conclusion
This project demonstrates the basic principles of building RESTful APIs using Spring Boot.
It includes CRUD functionality, REST controllers, database interaction with Spring Data JPA,
and API testing using Postman.
~~~~