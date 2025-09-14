# SuperFS - Microservices Project

This project is a **microservices-based system** built with **Spring Boot**, **Spring Cloud**, and **PostgreSQL/MongoDB**, combined with a **Micro Frontend (MFE)** architecture using **React, Vite, and Module Federation**.  

It demonstrates core microservices and frontend federation patterns such as **API Gateway, Feign Client, Circuit Breaker, JWT-based Authentication, and Micro Frontend composition**.  

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
- **Frontend (MFE)**
  - React + Vite + Module Federation
  - Independent deployable frontends (Auth App, Profile App, Dashboard Shell, etc.)
  - Shared UI components across MFEs
- **Database**
  - Mysql
- **Security**
  - JWT-based authentication

---

## 🛠️ Tech Stack
- **Backend:** Java, Spring Boot, Spring Cloud, Spring Security  
- **Frontend (MFE):** React, Vite, Module Federation  
- **Database:** PostgreSQL / MongoDB  
- **Service Discovery:** Eureka (optional)  
- **Resilience:** Resilience4j Circuit Breaker  
- **Build Tool:** Maven  
- **Containerization:** Docker & Kubernetes (optional)  

---

## 📂 Project Structure
