# Java Stack (JS) - 5th Semester Course (CT-23CT1506)

Welcome to the **Java Stack (JS)** repository for the 5th Semester, Section A, Session 2025-26 (ODD) at **Yeshwantrao Chavan College of Engineering, Nagpur**. This repository contains practical implementations and projects aligned with the course outcomes and lab objectives of the Java Stack (JS) curriculum.

## Course Outcomes
Upon successful completion of this course, students will be able to:
1. Apply OOP concepts to build backend applications with database integration.
2. Design responsive and interactive user interfaces using frontend technologies.
3. Develop full-stack applications integrating frontend, backend, and database with security.
4. Demonstrate ethics, communication, and teamwork in web project development.

## Lab Objectives
The practical labs are designed to provide hands-on experience in full-stack development. The key objectives include:
1. Introduction to Java and implementing basic programs (loops, conditionals, arrays).
2. Implementing OOP concepts (inheritance, polymorphism, encapsulation, abstraction).
3. Using collections and exception handling in Java.
4. Creating a simple RESTful API using Spring Boot.
5. Implementing CRUD operations using Spring Boot and JPA (Hibernate).
6. Connecting REST API to MySQL/PostgreSQL database.
7. Implementing validation and exception handling in Spring Boot.
8. Building a responsive UI using HTML, CSS, and Bootstrap.
9. Creating a dynamic UI using JavaScript (form validation, DOM manipulation).
10. Building a frontend application using Angular or React.
11. Connecting frontend with REST API (from Labs 4-6).
12. Writing unit tests using JUnit and integration tests with Mockito.
13. Implementing user authentication (e.g., JWT, Spring Security).
14. Building a complete mini-project with:
    - **Frontend**: Angular/React
    - **Backend**: Spring Boot, REST API
    - **Database**: MySQL/PostgreSQL

## Repository Structure
java-stack-ct23ct1506/ ├── lab-01/                # Basic Java programs (loops, conditionals, arrays) ├── lab-02/                # OOP concepts (inheritance, polymorphism, etc.) ├── lab-03/                # Collections and exception handling ├── lab-04/                # Simple RESTful API with Spring Boot ├── lab-05/                # CRUD operations with Spring Boot and JPA ├── lab-06/                # REST API with MySQL/PostgreSQL ├── lab-07/                # Validation and exception handling in Spring Boot ├── lab-08/                # Responsive UI with HTML, CSS, Bootstrap ├── lab-09/                # Dynamic UI with JavaScript ├── lab-10/                # Frontend application (Angular/React) ├── lab-11/                # Frontend-backend integration ├── lab-12/                # Unit and integration tests (JUnit, Mockito) ├── lab-13/                # User authentication (JWT, Spring Security) ├── mini-project/          # Full-stack mini-project │   ├── frontend/          # Angular/React frontend │   ├── backend/           # Spring Boot REST API │   ├── database/          # SQL scripts for MySQL/PostgreSQL ├── README.md              # This file ## Prerequisites
- **Java**: JDK 17 or higher
- **Maven**: For dependency management in Spring Boot projects
- **Node.js**: For Angular/React frontend development
- **MySQL/PostgreSQL**: Database server
- **IDE**: IntelliJ IDEA, VS Code, or Eclipse
- **Git**: For cloning and managing the repository
- **Postman**: For testing REST APIs

## Setup Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Siddheshpitale/java-stack-ct23ct1506.git
   cd java-stack-ct23ct1506
2. **Backend Setup (Spring Boot)**:
   Navigate to the specific lab or     mini-project/backend folder.
   Update application.properties       with your MySQL/PostgreSQL          database credentials.
   Run the project: mvn clean install
mvn spring-boot:run
3. **Database Setup**:
   Install MySQL or PostgreSQL.
   Create a database (e.g.,            java_stack_db).
   Run the SQL scripts in the          database/ folder to set up tables.
   Update database connection       details in the Spring Boot    application.properties.
4. **Frontend Setup (Angular/React)**:Navigate to the mini-project/frontend or specific lab folder.
Install dependencies: npm install
Start the frontend: npm start

5. **Testing**: For unit and integration tests, navigate to the relevant lab folder and run: mvn test
6. **API Testing**: Use Postman to test REST APIs (e.g., http://localhost:8080/api/...).
   
**Mini-Project**:
The mini-project folder contains a complete full-stack web application demonstrating the integration of frontend, backend, and database technologies. Key features include:
Frontend: Built using Angular or React, featuring a responsive user interface with dynamic components, form validation, and DOM manipulation. The UI is styled with HTML, CSS, and Bootstrap for a modern, user-friendly experience.
Backend: Developed using Spring Boot, providing a RESTful API with endpoints for CRUD operations. The backend implements secure user authentication using JWT and Spring Security, along with validation and exception handling for robust error management.
Database: Utilizes MySQL or PostgreSQL to store and manage application data. The database schema includes tables for user management, application-specific entities, and relationships, with SQL scripts provided for setup and sample data.
Functionality: The application supports user registration, login, and role-based access control. Users can perform CRUD operations (e.g., create, read, update, delete records) through the frontend, which communicates with the backend API. The system ensures data integrity and security.
Testing: Includes unit tests (using JUnit) for backend logic and integration tests (using Mockito) to verify API functionality and frontend-backend integration.
To run the mini-project:
Start the backend (Spring Boot).
Start the frontend (Angular/React).
Access the application at http://localhost:4200 (Angular) or http://localhost:3000 (React).
