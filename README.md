Financial Advisor Management System - Spring Boot with JPA
This project is part of a system designed to manage financial advisors, clients, portfolios, and securities using Spring Boot and Java Persistence API (JPA). The goal is to implement an effective object-relational mapping (ORM) system where Java objects are seamlessly persisted to a relational database.

📚 Project Overview
The project focuses on building a robust backend that:

Uses JPA for ORM to bridge Java objects and relational database tables.

Allows for automatic persistence and synchronization of Java objects with database records.

Handles complex data relationships with ease using Spring’s built-in JPA support.

✅ What I Did
Implemented the full data model based on the ERD created in the previous step.

Created entity classes for:

FinancialAdvisor

Client

Portfolio

Security

Set up relationships between these entities (one-to-many, many-to-one, etc.).

Properly annotated all entities with JPA annotations such as @Entity, @Id, @GeneratedValue, @OneToMany, @ManyToOne, and @JoinColumn.

Included constructors, getters, and setters for each class (excluding setters for IDs).

Managed data persistence and relationship mapping using Spring Data JPA.

⚙️ Technologies Used
Java

Spring Boot

Spring Data JPA

Relational Database (H2 or other)

IntelliJ IDEA

Git & GitHub

📂 Project Setup
Fork and Clone the starter repository.

Open in IntelliJ IDEA.

Build the project and explore the provided scaffolding.

Implement entity classes in the entities directory.

Annotate each class and configure the relationships.

Run the Spring Boot application to ensure proper database mapping.

📝 Key JPA Implementation Rules
Each entity is annotated with @Entity (from javax.persistence).

IDs are auto-generated using @Id and @GeneratedValue.

Relationships between entities are properly defined (one-to-many, many-to-one).

Each entity has:

Constructor initializing all instance variables.

Getters and setters for each instance variable (no setter for ID).

🚀 How to Run
Run the application directly from IntelliJ using Spring Boot’s built-in runner.

The application will automatically set up the database tables based on your JPA entities.

Data persistence will be managed automatically through the configured JPA repositories.

💻 Git & Version Control
All changes were committed and pushed regularly to the linked GitHub repository.

Proper version control practices were followed to track progress.# Task 2 Starter Repo
Contains Everything you need to get started on task 2 of Forage's Wells Fargo software engineering program
