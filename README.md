# Spring Boot Todo Application

A modern task management system built with Spring Boot and React, featuring CRUD operations, project management, and GitHub Gist integration.

## 🎥 Demo
[Watch Demo Video](your-video-url)

## ⚡ Key Features
- CRUD operations for tasks and projects
- User authentication system
- Project summary generation with GitHub Gist
- Search and filter capabilities
- Database persistence with MySQL

## 🛠️ Tech Stack
**Backend:**
- Spring Boot
- MySQL
- JPA/Hibernate
- Java 17

**Frontend:**
- React.js
- Vite
- Thymeleaf templates

## 🚀 Quick Start
1. Clone repository:

git clone https://github.com/yourusername/spring-boot-todo-manager

2. Configure database in application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/todomanager
spring.datasource.username=root
spring.datasource.password=root

3. Start services:

Backend
mvn spring-boot:run

Frontend
npm install
npm run dev


## 📁 Project Structure


spring-boot-todo/

├── src/

│   ├── main/

│   │   ├── java/

│   │   └── resources/

│   └── test/

├── frontend/

│   ├── src/

│   ├── public/

│   └── package.json

└── README.md


## 📚 API Documentation

POST /api/tasks - Create task

GET /api/tasks - List tasks

PUT /api/tasks/{id} - Update task

DELETE /api/tasks/{id} - Delete task

## 🔄 Usage Flow

Register/Login

Create project

Add tasks

Generate summary

View GitHub Gist

## 🌟 Future Scope

Task prioritization

Due date reminders

Team collaboration

Mobile app version

## 🤝 Contributing

Fork repository

Create feature branch

Commit changes

Push to branch

Open Pull Request


## 📄 License

This project is licensed under the MIT License [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)



