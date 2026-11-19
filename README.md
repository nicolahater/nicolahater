# Mykola Kantser

## Technical Skills

**Languages & Frameworks:** Java, Spring Boot, Spring MVC, Spring Data JPA, Spring Security, Hibernate, JDBC  
**Architecture & APIs:** Microservices, Distributed Systems, REST APIs, Event-Driven Architecture, OAuth2/OIDC, Keycloak  
**Data & Messaging:** SQL, PostgreSQL, Redis, AWS S3, Liquibase, Flyway, Kafka, RabbitMQ  
**Monitoring:** Grafana, Grafana Loki, Prometheus, Promtail, Tempo, OpenTelemetry  
**DevOps:** Docker, Kubernetes, GitLab CI/CD, GitHub Actions  
**Testing & Tools:** JUnit 5, Mockito, Maven, Gradle, Git, GitHub, GitLab

---

## 💼 Experience

### 🚀 [Microservices-Based Task Tracker](https://github.com/nicolahater/task-tracker)

- 🏗️ Designed and built a microservices-based task management system using **Java and Spring Boot**, separating authentication, task management, and notifications into independent services.
- 🌐 Implemented an **API Gateway with Spring Cloud Gateway**, handling routing, CORS, and request logging as the single entry point for all client traffic.
- 🔄 Built event-driven communication using **Apache Kafka** and the **Transactional Outbox pattern with Debezium CDC** to reliably deliver asynchronous events between microservices without dual-write inconsistencies.
- 📧 Integrated inter-service communication and developed scheduled background jobs for automated daily task summaries and email notifications.

### 🛒 [Product Catalogue Management System](https://github.com/nicolahater/shopit)

- 🏗️ Built a multi-module **Java application** for managing a product catalogue through a secured REST API and a web-based administration interface.
- 🔐 Integrated **Spring Security with Keycloak** using OAuth2/OIDC authentication and JWT-based authorization to secure application endpoints and inter-service communication.
- 🖥️ Built a server-rendered management interface using **Spring MVC and Thymeleaf**, integrating with the backend through Spring RestClient and OAuth2 bearer tokens.
- 🧪 Implemented unit and integration tests using **JUnit 5, Mockito, MockMvc, Testcontainers, and WireMock** to verify business logic, REST endpoints, database operations, and external service interactions.

### 🎾 [Tennis Scoreboard](https://github.com/nicolahater/tennis-scoreboard)

- 🎯 Developed a tennis match management application to automate score tracking, eliminate manual scoring errors, and ensure consistent enforcement of tennis rules.
- 🧠 Designed a rich domain model supporting **5+ scoring scenarios**, including deuce, advantage, tie-breaks, and automatic winner determination.
- 🗄️ Integrated **PostgreSQL and Hibernate ORM** to provide a persistent, searchable match history, optimizing queries with limit/offset pagination, sorting, player-based filtering, and elimination of the N+1 problem.
- ✅ Achieved **99% unit test coverage** of the domain layer using JUnit 5, helping ensure scoring correctness and prevent regressions in core business logic.
