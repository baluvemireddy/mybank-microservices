# Banking Microservices Application

A **Banking Microservices Application** built using **Java and Spring Boot**, following enterprise-grade microservices architecture principles.  
The system consists of independent services for **Accounts**, **Cards**, and **Loans**, with centralized configuration, service discovery, observability, and containerized deployment.

---

## 📌 Project Overview

This project demonstrates how real-world banking systems are designed using **Spring Cloud Microservices**.  
Each service is independently deployable, scalable, and communicates via REST APIs.

Key focus areas:
- Microservices architecture
- Centralized configuration
- Service discovery
- Fault tolerance & observability
- Docker-based deployment

---

## 🧱 Architecture

- **Config Server** – Centralized external configuration
- **Discovery Server (Eureka)** – Service registration & discovery
- **Accounts Service** – Manages customer account details
- **Cards Service** – Manages card-related information
- **Loans Service** – Manages loan-related data

Each service:
- Runs independently
- Uses its own database schema
- Exposes RESTful APIs

---

## 🛠️ Tech Stack

**Language**
- Java

**Frameworks & Libraries**
- Spring Boot
- Spring Cloud
- Spring Data JPA
- Spring Boot Actuator
- Resilience4j
- OpenAPI / Swagger

**Databases**
- MySQL

**DevOps & Tools**
- Docker
- Docker Compose
- Git
- Postman

---

## 🚀 Getting Started

### ✅ Prerequisites
- Java 11+
- Docker & Docker Compose
- Git

---

### 📥 Clone the Repository

```bash
git clone https://github.com/baluvemireddy/mybank-microservices.git
cd mybank-microservices
```
---

### 🐳 Run the Application

```bash
docker compose up --build
```
---