# 🚀 Skill Gap Analyzer API  
**Spring Boot Backend Project**

Skill Gap Analyzer is a backend system that helps identify the difference between a user’s current skills and the skills required for a target job role. This project focuses on clean backend architecture, scalable design, and real-world development practices.

---

## 🛠 Tech Stack

- **Java 24**
- **Spring Boot 4**
- Spring Data JPA
- MySQL
- Swagger (OpenAPI) *(for API documentation only)*
- Lombok
- Maven
- Postman

---

## 🏗 Architecture

Controller → Service → Repository → Database

This layered architecture ensures separation of concerns and scalability.

---

## 📦 Modules Implemented

### ✅ SGA0.1 — User Skill Management
- Create Users  
- Create Skills  
- Map Users with Skills  
- Track proficiency levels  

### ✅ SGA0.2 — Role Management System
- Create Roles  
- View All Roles  
- View Role by ID  
- Delete Role  

Roles represent **target job positions** used later for skill gap comparison.

---

## 🌐 API Endpoints (Current)

### 👤 Users & Skills

| Method | Endpoint | Description |
|--------|---------|-------------|
| POST | `/users` | Create user |
| GET | `/users` | Get all users |
| POST | `/skills` | Create skill |
| GET | `/skills` | Get all skills |
| POST | `/user-skills` | Map user to skill |

### 🎯 Roles

| Method | Endpoint | Description |
|--------|---------|-------------|
| POST | `/roles` | Create role |
| GET | `/roles` | Get all roles |
| GET | `/roles/{id}` | Get role by ID |
| DELETE | `/roles/{id}` | Delete role |

---

## 🗄 Database Tables

- `users`  
- `skills`  
- `user_skills`  
- `roles`  

---

## ▶️ Run Locally

1. Clone the repository  
2. Create MySQL database:

   CREATE DATABASE skillgap;

3. Update `application.yml` with DB credentials  
4. Run the Spring Boot application  

---

## 🧪 Testing

All APIs are tested using **Postman**.

---

## 🔮 Upcoming Modules

- SGA0.3 — RoleSkill Mapping  
- SGA0.4 — Skill Gap Analysis Engine  
- SGA0.5 — Skill Recommendation System  

---

## 👨‍💻 Author

Backend learning project focused on real-world architecture and clean code practices.
