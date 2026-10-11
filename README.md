# ExpertConnect Backend

Spring Boot REST API for ExpertConnect. The application uses Java 21, Maven, Spring Data JPA, Spring Security, JWT authentication, and MySQL.

## Requirements

- JDK 21 or newer
- MySQL 8

Create a database named `expertconnect`. Configure database and JWT settings with environment variables; see `.env.example` and `src/main/resources/application.properties`.

## Run locally

From this directory:

```powershell
.\mvnw.cmd spring-boot:run
```

The API runs at `http://localhost:8080` by default.

## Build and test

```powershell
.\mvnw.cmd clean test
.\mvnw.cmd clean package
```
