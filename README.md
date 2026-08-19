# 🏦 Banking Portal

A secure and scalable **Spring Boot banking application** built with JWT authentication, transaction processing, OTP verification, Redis/Caffeine caching, and MySQL.

## 🚀 Features

- 🔐 JWT authentication with Spring Security
- 👤 User registration and login
- 🏦 Bank account management
- 💰 Deposits, withdrawals, and inter-account transfers
- 📊 Transaction history
- 📧 Email OTP verification and password reset
- ⚡ Caffeine + Redis caching
- 📚 OpenAPI / Swagger documentation
- 🔍 PMD static code analysis
- 🧪 JUnit 5 + GreenMail testing
- 🐳 Docker support

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| Java 17/21 | Programming Language |
| Spring Boot 3.3.1 | Backend Framework |
| Spring Security + JWT | Authentication & Authorization |
| Spring Data JPA + Hibernate | ORM & Database Access |
| MySQL 8 | Relational Database |
| Redis 7 | Distributed Cache |
| Caffeine | Local Cache |
| MapStruct | DTO Mapping |
| Lombok | Boilerplate Reduction |
| Maven | Build Tool |
| Docker | Containerization |
| OpenAPI / Swagger | API Documentation |
| JUnit 5 + GreenMail | Testing |
| PMD | Static Code Analysis |

## 📂 Project Structure

```text
src/main/java/com/webapp/bankingportal/
├── config/        # Application configuration
├── controller/    # REST API endpoints
├── dto/           # Request and response DTOs
├── entity/        # JPA entities
├── exception/     # Custom exceptions & global handler
├── mapper/        # MapStruct mappers
├── repository/    # Spring Data JPA repositories
├── security/      # JWT & Spring Security
├── service/       # Business logic
└── util/          # Utility classes
