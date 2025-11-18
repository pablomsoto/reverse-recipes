# Gemini Project Configuration

This file helps the Gemini agent understand the specifics of the "reverse-recipes" project.

## 1. Project Overview

- **Name:** Reverse Recipes
- **Description:** A Spring Boot application. (Please provide a more detailed description).
- **Language:** Java
- **Framework:** Spring Boot
- **Build Tool:** Maven
- **Database:** SQL-based (inferred from Flyway migration).

## 2. Key Technologies & Libraries

- **Spring Boot:** Core application framework.
- **Flyway:** For database migrations, located in `src/main/resources/db/migration`.
- **Maven:** For dependency management and build process.
- **Testing:** JUnit 5 is likely used for tests in `src/test/java`.

## 3. Coding Conventions & Style

- Please follow standard Java and Spring Boot conventions.
- Adhere to the style of existing code in the project.

## 4. Important Commands

- **Build the project:** `./mvn clean install`
- **Run the application:** `./mvn spring-boot:run`
- **Run tests:** `./mvn test`

## 5. Directory Structure

- `src/main/java`: Main application source code.
- `src/main/resources`: Application configuration (`application.yml`), static assets, and database migrations.
- `src/test/java`: Test source code.
- `pom.xml`: Maven project configuration and dependencies.

## 6. Agent Behavior

- When modifying code, ensure all existing tests pass.
- When adding new features, please add corresponding tests.
