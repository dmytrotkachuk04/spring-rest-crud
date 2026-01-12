# Spring REST CRUD Application

This project is a simple Spring Boot REST application that demonstrates basic CRUD operations.

## Technologies
- Java 17
- Spring Boot
- Spring Web
- Spring Data JPA
- H2 Database
- Maven

## Description
The application provides a REST API to manage products.
Each product has an id, name, and price.

The project follows a layered architecture:
- Controller
- Service
- Repository
- Model (Entity)

## REST Endpoints

- GET /api/products  
  Returns a list of all products.

- GET /api/products/{id}  
  Returns a product by its id.

- POST /api/products  
  Creates a new product.

- PUT /api/products/{id}  
  Updates an existing product.

- DELETE /api/products/{id}  
  Deletes a product by its id.

## How to Run
1. Open the project in IntelliJ IDEA
2. Make sure Java 17 is selected
3. Run the Spring Boot application
4. The application starts on port 8080

## Testing
All endpoints were tested using Postman.
