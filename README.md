# Spring Boot Todo Application

A comprehensive To-Do Application built with Spring Boot backend and React frontend, featuring project and task management capabilities.

## 🌟 Description

A modern task management application that allows users to create projects, manage tasks, and generate project summaries with GitHub Gist integration.

## ✨ Features

- User authentication (Register/Login)
- Project management
- Task creation and management
- Project summary generation
- GitHub Gist integration
- Database persistence

## 🛠 Technologies Used

### Backend:
- Spring Boot
- MySQL
- JPA/Hibernate
- Java 17

### Frontend:
- React.js
- Vite
- npm packages

## 📦 Installation

1. **Download the Project**
 
 git clone <repository-url>

3. **Configure Database**

spring.datasource.url=jdbc:mysql://localhost:3306/todomanager
spring.datasource.username=root
spring.datasource.password=root

3. **Configure GitHub Token**

Generate a GitHub personal access token
Update token in GitHubGist.js

4.**Start Backend**
- ```bash
mvn spring-boot:run

5.**Start Frontend**
- ```bash
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

## Usage
Access the application at localhost:5173
Register a new account
Login with credentials
Create new projects
Add tasks to projects
Generate project summaries

## 🎯 Future Enhancements
Task prioritization
Due date reminders
Team collaboration features
Advanced project analytics
Mobile application

## 🤝 Contributing
Fork the repository
Create feature branch (git checkout -b feature/AmazingFeature)
Commit changes (git commit -m 'Add: Amazing Feature')
Push to branch (git push origin feature/AmazingFeature)
Open a Pull Request

## 📄 License
This project is licensed under the MIT License [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)



