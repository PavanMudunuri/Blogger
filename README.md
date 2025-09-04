# Blogger: Full-Stack Simple Blog Platform

A simple blog platform with user authentication, posts (with Markdown), categories, and comments.

**Tech Stack:**  
- Frontend: React  
- Backend: Spring Boot (Java)  
- Database: MySQL

## Features

- User registration, login, profile management (JWT auth)
- Create, read, update, delete blog posts (supports Markdown)
- Comment on posts
- Categorize posts
- Minimal, clean UI

---

## Setup Instructions

### 1. MySQL Setup

Create a DB called `blogdb` (or edit name in backend config).

```sql
CREATE DATABASE blogdb CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci;
```

### 2. Backend

```bash
cd backend
# Edit src/main/resources/application.properties with your MySQL username/password
./mvnw spring-boot:run
```
API runs at http://localhost:8080

### 3. Frontend

```bash
cd frontend
npm install
npm start
```
Runs at http://localhost:3000

---

> Backend: Spring Boot 3, JPA, JWT  
> Frontend: React 18, react-markdown, react-router-dom, axios

---