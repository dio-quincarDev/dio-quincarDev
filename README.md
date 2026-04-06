<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?lines=Backend%20Engineer;Java%20%7C%20Spring%20Boot;Clean%20Architecture&center=true&size=28&duration=4000&pause=800&color=2E8B57" />
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Java-17%2F21-D96C00?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=spring&logoColor=white"/>
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white"/>
</p>

<p align="center">
  Panama · GMT-5
</p>

---

## About

Backend Engineer focused on building secure and well-structured systems using Java and Spring.

Experience through hands-on projects with emphasis on:
- security (JWT, Spring Security)
- clean architecture
- maintainable design

---

## Engineering Focus

- REST API design (JWT / OAuth2)
- Spring Boot and Spring Security
- Hexagonal Architecture (Ports & Adapters)
- Role-based authorization
- Error handling and validation
- Relational database modeling
- SOLID principles and clean code

---

## Engineering Practices

- Environment-based configuration
- Modular project structure
- Separation of concerns
- Logging and debugging
- API documentation with Swagger (OpenAPI)

---

## Projects

### Employee Management System

REST API built using **hexagonal architecture**.

**Highlights:**
- Domain isolated from infrastructure
- Ports and adapters implementation
- Clean separation of business logic
- MySQL persistence
- Structured validation and error handling

**Stack:**
<p>
  <img src="https://img.shields.io/badge/Java-17-D96C00?style=flat&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=spring&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white"/>
</p>

https://github.com/dio-quincarDev/Gestion-de-Empleados

---

### Car Rental System

Reservation system with authentication and access control.

**Highlights:**
- JWT authentication
- Spring Security endpoint protection
- Business rules for availability

**Stack:**
<p>
  <img src="https://img.shields.io/badge/Java-21-D96C00?style=flat&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=flat&logo=spring&logoColor=white"/>
</p>

https://github.com/dio-quincarDev/ArrendadoraDeAutos

---

### Feature Flag API

Feature toggle system with **role-based authorization**.

**Highlights:**
- Feature activation/deactivation per user/role
- Role-based access control with Spring Security
- Dynamic feature management
- PostgreSQL persistence

**Stack:**
<p>
  <img src="https://img.shields.io/badge/Java-21-D96C00?style=flat&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=flat&logo=spring&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white"/>
</p>

https://github.com/dio-quincarDev/feat-flag-api-bytes-colabs

---

## Architecture

### System Overview

![Flowchart](https://imgr.whimsical.com/thumbnails/HLpUW98dhoNqaEeH466MYh/6WJ2CBNTAAwhjMa2WxyZFK)

### Authentication Flow (OAuth2 + JWT)

![Sequence](https://imgr.whimsical.com/thumbnails/JDParZFsDCnLkTipuTkStq/Kv95ehqJp3D5vkMNcN5Sq1)

---

### Key Architecture Decisions

- API Gateway as single entry point  
- Centralized authentication via Auth Service (OAuth2 + JWT)  
- Stateless security using JWT tokens  
- Role-based authorization handled by Spring Security  
- Microservices separation between Auth and Core domain  

---

### Request Lifecycle

1. Client request enters through API Gateway  
2. JWT token is validated  
3. Auth Service handles authentication when required  
4. Core Service processes business logic  
5. Data retrieved from PostgreSQL or Redis  
6. Response returned to client  

---

### Auth Service Responsibilities

- OAuth2 login (Google)  
- JWT generation and validation  
- Refresh token handling  
- Role-based access control  
- User and tenant resolution  

---

## Current Work

- Building Auth Service (OAuth2 + JWT, role-based access)  
- Designing microservices architecture with API Gateway  
- Implementing secure request flows and token validation  

---

## Stack

<p>
  <img src="https://img.shields.io/badge/Vue.js-3-4FC08D?style=flat&logo=vuedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/Swagger-85EA2D?style=flat&logo=swagger&logoColor=black"/>
</p>

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=dio-quincardev&show_icons=true&theme=tokyonight&hide_border=true&count_private=true"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dio-quincardev&layout=compact&theme=tokyonight&hide_border=true"/>
</p>

---

## Contact

<p align="center">
  <a href="https://linkedin.com/in/dio-quincar">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:dio-quincar@outlook.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>
