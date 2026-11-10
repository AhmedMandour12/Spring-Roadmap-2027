# Advanced – Stage Guide

**Build, secure, test, and deploy Spring Boot applications.**

[← Help Home](README.md) • [Advanced Resources](../Advanced/README.md)

---

## Stage Objective

Use Spring Boot and related technologies to build complete backend applications, secure APIs, test application behavior, and prepare applications for production.

## Recommended Sequence

### 1. Spring Boot Fundamentals

Learn how to create and configure Spring Boot applications.

Understand:

- Spring Initializr.
- Auto Configuration.
- Starter Dependencies.
- Embedded Servers.
- Properties and YAML.
- Profiles.
- Application structure.

**Milestone:** Create and run a basic Spring Boot application.

### 2. RESTful APIs & Spring MVC

Learn to expose application functionality through HTTP APIs.

Understand:

- Controllers and request mapping.
- HTTP methods and status codes.
- Request parameters and path variables.
- Request and response bodies.
- ResponseEntity.
- DTOs.
- Serialization and deserialization.
- CRUD operations.
- Pagination, sorting, and filtering.

**Milestone:** Build a REST API with complete CRUD operations.

### 3. Spring Data JPA

Integrate database persistence into Spring Boot applications.

Understand:

- Repository abstraction.
- JpaRepository.
- Derived queries.
- JPQL and native queries.
- Pagination and sorting.
- Transactions.
- Projections and Specifications.
- Query optimization and N+1 issues.

**Milestone:** Connect the REST API to a relational database.

### 4. Validation & Exception Handling

Validate incoming data and provide consistent error responses.

Understand:

- Bean Validation.
- Validation annotations.
- Custom validators.
- Global exception handling.
- Custom exceptions.
- Standardized error responses.

**Milestone:** Ensure invalid requests produce clear and consistent API errors.

### 5. Design Patterns & Application Architecture

Organize the application into maintainable components.

Understand:

- Layered architecture.
- Package by layer vs. package by feature.
- DTO and mapper patterns.
- Common design patterns.
- Separation of concerns.
- Clean Architecture fundamentals.

**Milestone:** Refactor the application into clear, maintainable modules.

### 6. Spring Security

Learn how to protect endpoints and manage application access.

Understand:

- Authentication and authorization.
- Security Filter Chain.
- UserDetails and UserDetailsService.
- PasswordEncoder.
- AuthenticationManager and AuthenticationProvider.
- Roles and authorities.
- Method security.
- CORS and CSRF.
- 401 and 403 responses.

**Milestone:** Secure endpoints and implement role-based access control.

### 7. JWT & Refresh Tokens

Understand token-based authentication and implement an appropriate token lifecycle.

Study:

- JWT structure and validation.
- Access tokens.
- Refresh tokens.
- JWT authentication filters.
- Token expiration.
- Refresh token rotation.
- Revocation and logout.

**Milestone:** Implement a secure token-based authentication flow.

### 8. Advanced Testing

Test application components and workflows.

Study:

- JUnit 5.
- Mockito.
- Unit testing.
- Integration testing.
- Spring Boot testing annotations.
- MockMvc.
- Testcontainers.

**Milestone:** Test controllers, services, repositories, and important application workflows.

### 9. API Documentation

Learn to document APIs using OpenAPI and Swagger UI.

**Milestone:** Publish interactive documentation for your API.

### 10. Additional Backend Topics

Explore relevant topics based on project requirements:

- File handling.
- Caching and Redis.
- Logging.
- Monitoring and Actuator.
- Rate limiting.
- WebSocket.
- MongoDB.
- Asynchronous processing.
- RabbitMQ and Kafka.

These are extensions to your core backend knowledge. Prioritize the technologies that solve real requirements in your projects.

### 11. Docker & Containerization

Learn:

- Images and containers.
- Dockerfile.
- Volumes and networks.
- Docker Compose.
- Containerizing Spring Boot.
- Running the application with a database.

**Milestone:** Run your backend and database using Docker Compose.

### 12. Deployment & CI/CD

Learn:

- Production builds.
- Environment variables and secrets.
- Linux and VPS basics.
- Domain and DNS.
- Nginx.
- HTTPS.
- GitHub Actions.
- Automated build, test, and deployment.

**Milestone:** Deploy your application and automate its deployment workflow.

---

## Completion Checklist

- [ ] Build RESTful APIs using Spring Boot.
- [ ] Integrate a relational database.
- [ ] Validate requests and handle exceptions.
- [ ] Organize application architecture.
- [ ] Secure APIs using Spring Security.
- [ ] Implement JWT authentication.
- [ ] Write unit and integration tests.
- [ ] Document APIs.
- [ ] Containerize the application.
- [ ] Deploy to a production environment.
- [ ] Configure a basic CI/CD workflow.

[Go to Final Project Guide →](06-PROJECT-GUIDE.md)

[← Help Home](README.md)
