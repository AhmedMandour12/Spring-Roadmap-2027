# Intermediate – Stage Guide

**Understand databases, persistence, and the Spring Framework Core.**

[← Help Home](README.md) • [Intermediate Resources](../Intermediate/README.md)

---

## Stage Objective

Learn how Java applications interact with relational databases, understand ORM and persistence, and become familiar with the core mechanisms of the Spring Framework.

## Recommended Sequence

### 1. Database & SQL

Start with relational database fundamentals and SQL.

Study:

- Relational database concepts.
- Tables, keys, and constraints.
- ER diagrams and database design.
- DDL, DML, and DQL.
- Filtering, sorting, and aggregation.
- Joins and subqueries.
- CTEs.
- Normalization.
- Indexes.
- Transactions and ACID properties.

**Practice:** Solve SQL exercises and design a database for a small application.

### 2. JDBC

Understand how Java communicates directly with relational databases.

Study:

- JDBC architecture and drivers.
- Connection and DriverManager.
- Statement and PreparedStatement.
- ResultSet.
- CRUD operations.
- Transactions.
- Commit and rollback.
- DAO pattern.

**Practice:** Build a Java application that performs CRUD operations using JDBC.

### 3. JPA & Hibernate

Learn ORM and how Java objects are mapped to database tables.

Study:

- ORM concepts.
- JPA vs. Hibernate.
- Entity mapping.
- Entity lifecycle.
- Primary-key generation strategies.
- Entity relationships.
- Lazy and eager fetching.
- Cascade types.
- Persistence Context.
- JPQL and native queries.
- Transactions.

**Practice:** Map related entities and implement database operations using Hibernate.

### 4. Spring Framework Core

Understand the concepts that make Spring applications work.

Study:

- Inversion of Control.
- Dependency Injection.
- IoC Container.
- ApplicationContext.
- Spring Beans.
- Bean lifecycle and scopes.
- Component scanning.
- Annotation-based configuration.
- Java-based configuration.
- Introduction to AOP.

**Practice:** Create a small Spring Core application with multiple components and inject dependencies using constructor injection.

---

## Suggested Practical Project

**Inventory Management System**

Implement:

- Product and category management.
- Database schema and relationships.
- CRUD operations.
- JDBC-based database access.
- Hibernate entity mapping.
- Spring Core component configuration.

Build the project incrementally. You can first implement database operations using JDBC, then explore how ORM changes the persistence layer.

## Completion Checklist

- [ ] Design a relational database.
- [ ] Write SQL queries confidently.
- [ ] Use JDBC and PreparedStatement.
- [ ] Manage database transactions.
- [ ] Understand ORM, JPA, and Hibernate.
- [ ] Map entity relationships.
- [ ] Understand entity lifecycle and Persistence Context.
- [ ] Explain IoC and Dependency Injection.
- [ ] Configure and manage Spring Beans.
- [ ] Build a small application using Spring Core.
- [ ] Publish the project on GitHub.

## Before Moving to Advanced

You should understand how data is stored and retrieved, how Java objects map to database records, and how Spring manages application components.

[Go to Advanced Level →](../Advanced/README.md)

[← Help Home](README.md)
