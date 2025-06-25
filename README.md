
# 🛍️ E-commerce Backend API using Spring Boot

## 🚀 Overview
A simple backend API for an E-commerce application built with **Spring Boot**. 
This project includes CRUD operations for managing product categories. 
It demonstrates Spring Boot REST API design, JPA for database interaction, and standard service-repository patterns.

---

##  Tech Stack
-  Java 17+
-  Spring Boot
-  Spring Data JPA (Hibernate)
-  MySQL (or any other SQL DB)
-  REST API
-  Maven

---

## 🔥 Features
-  Category Management (CRUD)
-  Exception Handling with meaningful HTTP status codes
-  Clean and modular code structure
-  API Documentation (Optional: Swagger can be added)

---

## 📁 Project Structure
```
src
 └── main
     ├── java
     │   └── com.ecommerce.project
     │       ├── controller
     │       ├── model
     │       ├── repositories
     │       ├── service
     │       └── SbEcomApplication.java
     └── resources
         ├── application.properties
```

---

## ⚙️ Installation & Setup

### 🖥️ Prerequisites:
- Java 17+
- Maven
- MySQL running locally

### 🔥 Steps:

 **Configure DB in `application.properties`:**
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce_db
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update
```

3. **Run the App:**
```bash
./mvnw spring-boot:run
```
or run `SbEcomApplication.java` from your IDE.

4. **API Test:**  
Use tools like Postman to hit endpoints like:
- `GET /api/categories`
- `POST /api/categories`
- `PUT /api/categories/{id}`
- `DELETE /api/categories/{id}`

---

## 🔑 API Endpoints Example

| Method | Endpoint                  | Description        |
|--------|----------------------------|--------------------|
| GET    | `/api/categories`          | List categories    |
| POST   | `/api/categories`          | Add category       |
| PUT    | `/api/categories/{id}`     | Update category    |
| DELETE | `/api/categories/{id}`     | Delete category    |

---


## 🌟 Future Improvements
- Product, User, and Order APIs
- JWT-based Authentication & Authorization
- Swagger UI for API documentation
- CI/CD pipeline
- Unit and Integration tests

---

## 👩‍💻 Author
**Janhvi 🚀**  
*Engineering student, backend dev in progress, coffee-powered coder.*  
---

## 💌 Note
> This project is part of my learning journey.
