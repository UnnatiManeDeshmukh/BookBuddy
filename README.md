# 📚 BookBuddy - Book Request and Approval System

A simple full-stack web application that allows users to request books and lets the admin approve or deny them. Built using **Spring Boot**, **PostgreSQL**, and **HTML/CSS/JavaScript**.

---

## 🙋‍♀️ Developed By

- Unnati Mane Deshmukh

---

## 🛠️ Technologies Used

**Backend (Spring Boot):**
- Java 21
- Spring Web
- Spring Data JPA (Hibernate)
- PostgreSQL
- Maven

**Frontend:**
- HTML
- CSS
- JavaScript

**Tools:**
- Spring Tool Suite (STS)
- Postman (for API testing)
- GitHub

---

## 🌐 Live Features

- 📥 Book request form for users
- 🔐 Admin login with password
- ✅ Approve or ❌ Deny book requests
- 📄 View all requests in tabular format
- 🔁 Instant reload after actions
- ☁️ Fully responsive UI

---

## 🧾 API Endpoints

| Method | Endpoint                        | Description               |
|--------|----------------------------------|--------------------------|
| POST   | `/api/request`                  | Submit a book request     |
| GET    | `/api/request`                  | Get all requests          |
| PUT    | `/api/request/{id}/approve`     | Approve a request         |
| DELETE | `/api/request/{id}`             | Deny (delete) a request   |

---

## 📁 Project Structure

```
BookBuddy/
├── backend/
│   ├── src/
│   │   └── main/java/com/example/bookbuddy/
│   │       ├── controller/        # REST API Controllers
│   │       ├── model/             # Entity classes (BookRequest.java)
│   │       ├── repository/        # JPA Repositories
│   │       └── service/           # Business Logic
│   ├── resources/
│   │   └── application.properties # DB Config
│   └── pom.xml                    # Maven configuration
│
├── frontend/
│   ├── index.html                 # User + Admin Interface
│   └── background.png             # Background Image
```

---

## 🔐 Admin Access

| Username | Password |
|----------|----------|
| admin    | **unnu** |

Only admin can see the full list of book requests and perform actions.

---

## ▶ How to Run

### 1️⃣ Backend

- Configure `application.properties`:
```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/bookbuddy
spring.datasource.username=postgres
spring.datasource.password=unnati22
spring.jpa.hibernate.ddl-auto=update
server.port=7777

