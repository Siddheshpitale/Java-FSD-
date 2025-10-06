Java Stack (JS) - 5th Semester Course (CT-23CT1506)
Welcome to the Java Stack (JS) repository for the 5th Semester, Section A, Session 2025-26 (ODD) at Yeshwantrao Chavan College of Engineering, Nagpur. This repository contains practical implementations and projects aligned with the course outcomes and lab objectives of the Java Stack (JS) curriculum.
Course Overview
The Java Stack (JS) course focuses on building full-stack web applications using Java-based technologies, frontend frameworks, and database integration. The course equips students with the skills to design, develop, and test secure and responsive web applications while fostering teamwork, ethics, and effective communication.
Course Outcomes
Upon successful completion of this course, students will be able to:
Apply OOP concepts to build backend applications with database integration.
Design responsive and interactive user interfaces using frontend technologies.
Develop full-stack applications integrating frontend, backend, and database with security.
Demonstrate ethics, communication, and teamwork in web project development.
Lab Objectives
The practical labs are designed to provide hands-on experience in full-stack development. The key objectives include:
Introduction to Java and implementing basic programs (loops, conditionals, arrays).
Implementing OOP concepts (inheritance, polymorphism, encapsulation, abstraction).
Using collections and exception handling in Java.
Creating a simple RESTful API using Spring Boot.
Implementing CRUD operations using Spring Boot and JPA (Hibernate).
Connecting REST API to MySQL/PostgreSQL database.
Implementing validation and exception handling in Spring Boot.
Building a responsive UI using HTML, CSS, and Bootstrap.
Creating a dynamic UI using JavaScript (form validation, DOM manipulation).
Building a frontend application using Angular or React.
Connecting frontend with REST API (from Labs 4-6).
Writing unit tests using JUnit and integration tests with Mockito.
Implementing user authentication (e.g., JWT, Spring Security).
Building a complete mini-project with:
Frontend: Angular/React
Backend: Spring Boot, REST API
Database: MySQL/PostgreSQL
Repository Structure
The repository is organized into folders corresponding to each lab objective and the final mini-project. Below is the structure:
java-stack-ct23ct1506/
├── lab-01/                # Basic Java programs (loops, conditionals, arrays)
├── lab-02/                # OOP concepts (inheritance, polymorphism, etc.)
├── lab-03/                # Collections and exception handling
├── lab-04/                # Simple RESTful API with Spring Boot
├── lab-05/                # CRUD operations with Spring Boot and JPA
├── lab-06/                # REST API with MySQL/PostgreSQL
├── lab-07/                # Validation and exception handling in Spring Boot
├── lab-08/                # Responsive UI with HTML, CSS, Bootstrap
├── lab-09/                # Dynamic UI with JavaScript
├── lab-10/                # Frontend application (Angular/React)
├── lab-11/                # Frontend-backend integration
├── lab-12/                # Unit and integration tests (JUnit, Mockito)
├── lab-13/                # User authentication (JWT, Spring Security)
├── mini-project/          # Full-stack mini-project
│   ├── frontend/          # Angular/React frontend
│   ├── backend/           # Spring Boot REST API
│   ├── database/          # SQL scripts for MySQL/PostgreSQL
├── docs/                  # Additional documentation (if any)
├── README.md              # This file
└── LICENSE                # License file (if applicable)
Prerequisites
To run the projects in this repository, ensure you have the following installed:
Java: JDK 17 or higher
Maven: For dependency management in Spring Boot projects
Node.js: For Angular/React frontend development
MySQL/PostgreSQL: Database server
IDE: IntelliJ IDEA, VS Code, or Eclipse
Git: For cloning and managing the repository
Postman: For testing REST APIs
Docker (optional): For containerized database setup
Setup Instructions
Clone the Repository:
git clone https://github.com/Siddheshpitale/java-stack-ct23ct1506.git
cd java-stack-ct23ct1506
Backend Setup (Spring Boot):
Navigate to the specific lab or mini-project/backend folder.
Update application.properties with your MySQL/PostgreSQL database credentials.
Run the project:
mvn clean install
mvn spring-boot:run
Database Setup:
Install MySQL or PostgreSQL.
Create a database (e.g., java_stack_db).
Run the SQL scripts in the database/ folder to set up tables.
Update database connection details in the Spring Boot application.properties.
Frontend Setup (Angular/React):
Navigate to the mini-project/frontend or specific lab folder.
Install dependencies:
npm install
Start the frontend:
npm start
Testing:
For unit and integration tests, navigate to the relevant lab folder and run:
mvn test
API Testing:
Use Postman to test REST APIs (e.g., http://localhost:8080/api/...).
Mini-Project
The mini-project folder contains a complete full-stack application with:
Frontend: Built using Angular/React with responsive UI and form validation.
Backend: Spring Boot REST API with CRUD operations and JWT-based authentication.
Database: MySQL/PostgreSQL with schema and sample data.
To run the mini-project:
Start the backend (Spring Boot).
Start the frontend (Angular/React).
Access the application at http://localhost:4200 (Angular) or http://localhost:3000 (React).
Contributing
This repository is primarily for academic purposes. Contributions are welcome for improving code quality, fixing bugs, or adding documentation. To contribute:
Fork the repository.
Create a new branch (git checkout -b feature-branch).
Commit your changes (git commit -m "Add feature").
Push to the branch (git push origin feature-branch).
Create a Pull Request.
License
This project is licensed under the MIT License (or specify another license if applicable).
Contact
For queries, reach out to the course instructor at Yeshwantrao Chavan College of Engineering, Nagpur, or contact the repository maintainer at [siddheshpitale@gmail.com].
