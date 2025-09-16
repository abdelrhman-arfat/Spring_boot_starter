# Spring Boot Starter Project with Docker

A starter template for Spring Boot applications, fully configured for Docker. Includes best practices for project structure, database integration, and containerization.

---

## Project Structure

```bash
project-name/
├── src/main/java/com/project/handly
│ ├── Entities/ # JPA Entities
│ ├── Enum/ # Enum classes
│ ├── Repositories/ # Spring Data JPA Repositories
│ ├── Services/ # Business logic
│ ├── Controllers/ # REST controllers
│ └── Config/ # Security, Swagger, other configurations
├── src/main/resources
│ ├── application.properties
│ └── db/migration/ # Flyway migration scripts
├── Dockerfile
├── docker-compose.yml
├── pom.xml
└── README.md
```


---

## Features

- Spring Boot REST API  
- PostgreSQL Database integration  
- Flyway DB migrations  
- JPA Entities with relationships  
- Soft delete functionality (`is_deleted`)  
- Dockerized environment  
- Password encoding & basic authentication setup  
- Starter template for rapid development  

---

## Prerequisites

- Java 21+  
- Maven  
- Docker  
- Docker  
- PostgreSQL (Dockerized or local)  

---

.env
```bash
SPRING_PROFILES_ACTIVE=dev
SPRING_DEVTOOLS_RESTART_ENABLED=true

JWT_SECRET_KEY=
```

## Getting Started

1. **Clone the repository**

```bash
git clone https://github.com/abdelrhman-arfat/Spring_boot_starter.git
cd project-name
```
