# SuperFS - Microservices Project

This project is a **microservices-based system** built with **Spring Boot**, **Spring Cloud**, and **PostgreSQL/MongoDB**.  
It demonstrates core microservices patterns such as **API Gateway, Feign Client, Circuit Breaker, and JWT-based Authentication**.  

---

## 🚀 Features
- **Auth Service**
  - User registration & login
  - JWT authentication & logout
  - Inter-service user management via OpenFeign
- **Profile Service**
  - Fetch user details via Auth Service
  - Update user information
  - Resilience with Circuit Breaker & Fallbacks
- **API Gateway**
  - Single entry point for all microservices
  - Centralized CORS and route management
- **Database**
  - PostgreSQL or MongoDB (configurable)
- **Security**
  - JWT-based authentication

---

## 🛠️ Tech Stack
- **Backend:** Java, Spring Boot, Spring Cloud, Spring Security  
- **Database:** PostgreSQL / MongoDB  
- **Service Discovery:** Eureka (optional)  
- **Resilience:** Resilience4j Circuit Breaker  
- **Build Tool:** Maven  
- **Containerization:** Docker & Kubernetes (optional)  
- **Frontend (planned):** React  

---

## 📂 Project Structure
