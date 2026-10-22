<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?lines=Backend%20Engineer;Java%20%7C%20Spring%20Security;Clean%20Architecture&center=true&size=28&duration=4000&pause=800&color=2E8B57" />
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Java-17%2F21-D96C00?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=spring&logoColor=white"/>
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
</p>

---

# Backend Engineer & SaaS-Oriented Architect

### Spring Security · System Design · Clean Architecture

Focused on building secure, scalable backend systems using Java and Spring.

My approach goes beyond implementation — I design **systems with clear boundaries, strong security, and maintainable structure**, aligned with real-world SaaS patterns.

---

## Currently building

**Pymeq — Forensic Accounting for Small Business**  
[Repository](https://github.com/dio-quincarDev/pymes-admin) · Beta

- Multi-tenant SaaS with dedicated auth, gateway and core services
- OAuth2 (Google) login and stateless JWT, with token blacklist on Redis
- API Gateway as single entry point; internal services run on an isolated network
- CI/CD on GitHub Actions: build, tests, security check, staging and production deploys
- Multi-architecture images (`linux/amd64`, `linux/arm64`) via QEMU and Docker Buildx
- Branch workflow `feature → develop → main`

Current focus: auth service and edge validation at the gateway.

---

## Engineering Focus

- **Security First**
  - JWT-based stateless authentication
  - OAuth2 flows (Google login)
  - Role-based authorization with Spring Security
  - Token validation strategies

- **System Design**
  - API Gateway as single entry point
  - Separation between Auth and Core services
  - Request lifecycle design and validation flow

- **Architecture**
  - Modular services behind a single gateway (Auth and Core)
  - Domain modules with their own controller, service and repository
  - One PostgreSQL instance with an isolated schema per service

---

## Architecture

![Authentication flow](https://raw.githubusercontent.com/dio-quincarDev/pymes-admin/main/backend/auth/docs/strategies/pymes-auth-flow.png)

Credentials go through the API Gateway to the Auth Service: Redis applies the rate limit, PostgreSQL resolves the user and tenant, the audit log is written, and the access and refresh tokens are issued. On later requests the gateway validates the JWT against the Redis blacklist and forwards the request with identity headers.

---

### Key Decisions

- API Gateway as centralized entry point  
- Stateless authentication using JWT  
- Token validation at Gateway level  
- Role-based access control via Spring Security  
- Separation between authentication and business logic  

---

## Featured Projects

### [Fleet Control](https://github.com/dio-quincarDev/fleet-control)

Fleet management backend built with a microservices architecture: 9 autonomous services, with CI/CD pipelines and seeded demo data.

**Stack:**
Java · Spring Boot · Docker · GitHub Actions

---

### [Employee Management System](https://github.com/dio-quincarDev/gestion-de-empleados)

REST API built using hexagonal architecture.

**Highlights:**
- Domain isolated from infrastructure
- Ports and adapters implementation
- Structured validation and error handling
- Database migrations with Flyway

**Stack:**
Java · Spring Boot · MySQL · Flyway

---

### [Feature Flag API](https://github.com/dio-quincarDev/feat-flag-api-bytes-colabs)

Feature toggle system with fine-grained authorization.

**Highlights:**
- Feature activation per role/user
- Authorization with Spring Security
- Scalable toggle design

**Stack:**
Java · Spring Security · PostgreSQL

---

### [Portfolio](https://github.com/dio-quincarDev/portfolio)

Personal site, deployed on Oracle Cloud Infrastructure Free Tier.

**Stack:**
Quasar · Vue 3 · Docker · GitHub Actions · Nginx

**Live:** [https://dioquincar.dev](https://dioquincar.dev)

---

## Engineering Practices

- Modular and maintainable project structure  
- Clear separation of responsibilities  
- Environment-based configuration  
- API documentation with Swagger (OpenAPI)  
- Secure request flows  
- Pull requests with CI checks before merge  

---

## Stack

**Backend**
- Java 17/21
- Spring Boot
- Spring Security
- JWT / OAuth2

**Data**
- PostgreSQL
- MySQL
- Redis

**Tools**
- Docker (Buildx, multi-architecture)
- GitHub Actions
- Git
- Swagger / OpenAPI
- Nginx / Caddy

**Frontend**
- Vue 3

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=dio-quincarDev&theme=tokyonight&hide_border=true" alt="GitHub Streak"/>
</p>

---

## Contact

**Portfolio:** [https://dioquincar.dev](https://dioquincar.dev)

<p align="center">
  <a href="https://linkedin.com/in/dioquincar">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:dio-quincar@outlook.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>
