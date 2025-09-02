Simple Student Login Spring Boot Application

Welcome to the Simple Student Login application! This project is a basic Spring Boot application designed to help new Java developers understand the fundamentals of a modern web application using Spring Boot. It uses a PostgreSQL database and Maven for dependency management.

🛠️ Technologies Used

    Java 17: The core programming language for the application.

    Spring Boot: The framework used to create a production-ready, standalone application.

    Maven: The build automation tool used to manage project dependencies and build the application.

    PostgreSQL: The relational database used to store student data.

⚙️ Project Features

    Student Model: A Student model with the following entities:

        id

        name

        email

        address

    Database Integration: The application connects to a PostgreSQL database, with the table named student_details.

    Basic CRUD Operations: It will support basic operations (Create, Read, Update, Delete) for student records.

🚀 Getting Started

Prerequisites

To run this project, you'll need the following installed on your machine:

    JDK 17

    Maven (a compatible version, usually included with IDEs like IntelliJ IDEA or Eclipse)

    PostgreSQL database

Database Setup:

    Make sure your PostgreSQL server is running.

    Create a new database for this project.

    Update the database connection properties in the src/main/resources/application.properties file with your database credentials:

Run the Application:

    You can run the application directly from your IDE by running the main class.

    Alternatively, use Maven from the command line:

Bash

    mvn spring-boot:run

