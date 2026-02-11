# Product Service - Spring Boot Microservice

## 📌 Project Overview

This project is a RESTful microservice developed using Spring Boot as part of DevOps Lab 03.  
The application provides CRUD operations for managing products and demonstrates the use of:

- Spring Boot REST APIs
- H2 In-Memory Database
- Spring Data JPA
- Swagger (OpenAPI) Documentation

---

## 🚀 Key Features

- RESTful API implementation
- CRUD operations for products
- In-memory database using H2
- API documentation using Swagger UI

---

## 🛠 Technologies Used

- Java 17
- Spring Boot
- Spring Data JPA
- H2 Database
- Swagger (OpenAPI)
- Maven

---

## ▶️ How to Run

Run using Maven Wrapper:

    .\mvnw.cmd spring-boot:run

---

## 🌐 Access

Swagger:
http://localhost:8080/swagger-ui/index.html

H2 Console:
http://localhost:8080/h2-console

JDBC URL: jdbc:h2:mem:testdb
Username: sa
Password: (empty)

---

## 📡 API Endpoints

POST   /products  
GET    /products  
GET    /products/{id}  
DELETE /products/{id}

---
