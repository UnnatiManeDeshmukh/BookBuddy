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
|--------|----------------------------------|---------------------------|
| POST   | `/api/request`                  | Submit a book request     |
| GET    | `/api/request`                  | Get all requests          |
| PUT    | `/api/request/{id}/approve`     | Approve a request         |
| DELETE | `/api/request/{id}`             | Deny (delete) a request   |

---

## 📂 Project Structure

