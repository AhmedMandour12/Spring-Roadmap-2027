
<div align="center">

# SPRING BOOT BACKEND ROADMAP

### INTERMEDIATE LEVEL

**From Java Foundations to Enterprise Application Development.**

Build your understanding of databases, persistence technologies, and the Spring Framework to prepare for developing real-world backend applications.

[← Beginner Level](../Beginner/README.md) • [Main Roadmap](../README.md)

</div>

---

## TABLE OF CONTENTS

| # | Section | Priority |
|:---:|---|:---:|
| 01 | [Database & SQL](#01--database--sql) | Required |
| 02 | [Java Database Connectivity (JDBC)](#02--java-database-connectivity-jdbc) | Required |
| 03 | [JPA & Hibernate](#03--jpa--hibernate) | Required |
| 04 | [Spring Framework Core](#04--spring-framework-core) | Required |
| 05 | [Practical Application](#05--practical-application) | Required |
| 06 | [Recommended Books](#06--recommended-books) | Reference |

---

## ABOUT THIS LEVEL

Welcome to the Intermediate Level!

In this stage, you will move beyond Java programming fundamentals and start learning the technologies and concepts used to build professional backend applications.

You will develop a solid understanding of relational databases, SQL, database connectivity, ORM technologies, and the core concepts of the Spring Framework.

**By the end of this level, you should be able to:**

- Design and interact with relational databases.
- Write SQL queries to retrieve and manipulate data.
- Connect Java applications to databases using JDBC.
- Understand ORM concepts and work with JPA and Hibernate.
- Understand the architecture and core concepts of the Spring Framework.
- Apply Dependency Injection and Inversion of Control.
- Organize Java applications using Spring components and configurations.

> **Learning Approach:** Follow the learning path in order. Focus on understanding the underlying concepts before moving to the next technology.

---

## LEARNING PATH

### 01 — Database & SQL

**Objective:** Understand relational database concepts, learn how to design databases, and master SQL for managing and manipulating data.

#### A. Database Fundamentals

**Note:** You can choose ONE of the following learning paths.

##### MaharaTech

| Learning Resources | Type |
|---|---|
| [Database Fundamentals – MaharaTech](https://maharatech.gov.eg/course/view.php?id=740) | Recommended |

**Note:** يجب تسجيل الدخول إلى الموقع أولًا حتى تتمكن من الالتحاق بالكورس ومتابعة المحتوى.

##### Mohamed El Desouky

| Learning Resources | Type |
|---|---|
| [Database Fundamentals – Mohamed El Desouky](https://www.youtube.com/playlist?list=PL37D52B7714788190) | Comprehensive Playlist |

##### Harvard University – CS50 SQL

| Learning Resources | Type |
|---|---|
| [CS50's Introduction to Databases with SQL](https://learning.edx.org/course/course-v1:HarvardX+CS50SQL+SQL/home) | Comprehensive Course |

**Note:** يجب تسجيل الدخول إلى الموقع، ثم اختيار الدراسة بدون شهادة (Audit / Free Track) بدلًا من شراء الشهادة.

#### B. Additional Database Resources

These resources can be used as alternative learning paths or additional references.

| Learning Resources | Type |
|---|---|
| [SQL Bootcamp – Zero to Hero](https://www.youtube.com/playlist?list=PLNcg_FV9n7qZY_2eAtUzEUulNjTJREhQe) | Additional Playlist |

#### C. SQL Practice

**Objective:** Strengthen your SQL skills through practical exercises and database challenges.

| Learning Resources | Type |
|---|---|
| [LeetCode – Top SQL 50](https://leetcode.com/studyplan/top-sql-50/) | 50 SQL Problems |

**Topics to Master**

- Relational Database Concepts.
- Database Design and ERD.
- Tables, Rows, and Columns.
- Primary Keys and Foreign Keys.
- SQL Data Types.
- DDL, DML, and DQL.
- SELECT, INSERT, UPDATE, and DELETE.
- Filtering and Sorting.
- Aggregate Functions.
- GROUP BY and HAVING.
- Joins (INNER, LEFT, RIGHT, FULL).
- Subqueries.
- Common Table Expressions (CTEs).
- Database Normalization.
- Constraints.
- Views.
- Stored Procedures.
- Indexes.
- Transactions and ACID Properties.

---

### 02 — Java Database Connectivity (JDBC)

**Objective:** Understand how Java applications communicate with relational databases and perform database operations using JDBC.

| Learning Resources | Type |
|---|---|
| [Java Database Connectivity – MaharaTech](https://maharatech.gov.eg/course/view.php?id=2246) | Recommended Course |
| [Java JDBC Tutorial – 4Programmer (Luv2Code)](https://4programmer.com/ar/59/java-jdbc-tutorial) | Additional Course |

**Topics to Master**

- Introduction to JDBC.
- JDBC Architecture.
- JDBC Drivers.
- DriverManager.
- Connection.
- Statement and PreparedStatement.
- ResultSet.
- Executing SQL Queries.
- CRUD Operations.
- SQL Injection and PreparedStatement.
- JDBC Transactions.
- Commit and Rollback.
- Batch Processing.
- Database Metadata.
- DAO Pattern.
- Database Configuration.

**Practical Focus**

Build a Java application that connects to a relational database and performs CRUD operations using JDBC.

---

### 03 — JPA & Hibernate

**Objective:** Understand Object-Relational Mapping (ORM) and learn how to map Java objects to database tables using JPA and Hibernate.

| Learning Resources | Type |
|---|---|
| [JPA & Hibernate Fundamentals 2023 – Luv2Code](https://www.classcentral.com/course/youtube-jpa-hibernate-fundamentals-2023-289561) | Comprehensive Course |
| [Hibernate & JPA Tutorial – Crash Course](https://www.youtube.com/watch?v=xHminZ9Dxm4) | Additional Resource |

**Topics to Master**

#### A. ORM Fundamentals

- What is ORM?
- Why ORM?
- JPA vs. Hibernate.
- Entity Mapping.
- Entity Classes.
- Persistence Unit.
- EntityManager.

#### B. Entity Lifecycle

- Transient State.
- Persistent State.
- Detached State.
- Removed State.
- Persist.
- Merge.
- Remove.
- Refresh.
- Detach.

#### C. Entity Mapping & Relationships

- @Entity.
- @Table.
- @Id.
- @GeneratedValue.
- Generation Strategies.
- @Column.
- @OneToOne.
- @OneToMany.
- @ManyToOne.
- @ManyToMany.
- @JoinColumn.
- @JoinTable.
- Owning Side vs. Inverse Side.

#### D. Advanced Persistence Concepts

- Cascade Types.
- Fetch Types (Lazy & Eager).
- Persistence Context.
- First-Level Cache.
- JPQL.
- Native Queries.
- Transactions.
- Entity Relationships Management.
- N+1 Query Problem (Introduction).

**Important:** Pay special attention to entity relationships, cascade operations, fetch types, and the entity lifecycle. These concepts are essential when working with Spring Data JPA later.

---

### 04 — Spring Framework Core

**Objective:** Understand the fundamental architecture of the Spring Framework and learn how it manages application objects and their dependencies.

| Learning Resources | Type |
|---|---|
| [Spring Framework Core – Java Brains](https://www.youtube.com/watch?v=ZwcHeLhvuq4&list=PLSVW22jAG8pCKcoHpnCh1cUeQJ8Aazchn&index=8) | Video / Playlist |

**Topics to Master**

#### A. Introduction to Spring

- What is Spring Framework?
- Why Spring?
- Spring Architecture.
- Spring Modules.
- Traditional Java Applications vs. Spring Applications.

#### B. Inversion of Control (IoC)

- What is Inversion of Control?
- Why IoC?
- IoC Container.
- ApplicationContext.
- BeanFactory.
- Dependency Management.

#### C. Dependency Injection (DI)

- What is Dependency Injection?
- Constructor Injection.
- Setter Injection.
- Field Injection.
- Dependency Injection vs. Inversion of Control.

#### D. Spring Beans

- What is a Spring Bean?
- Bean Lifecycle.
- Bean Scopes.
- Singleton and Prototype.
- Bean Configuration.
- Component Scanning.

#### E. Spring Configuration

- @Configuration.
- @Bean.
- @Component.
- @Service.
- @Repository.
- @Autowired.
- @ComponentScan.
- Java-Based Configuration.

#### F. Additional Concepts

- Annotation-Based Configuration.
- XML-Based Configuration (Introduction).
- Bean Dependencies.
- Qualifiers and Primary.
- Introduction to Aspect-Oriented Programming (AOP).

**Important:** Make sure you understand IoC, Dependency Injection, Spring Beans, and ApplicationContext before moving forward. These concepts are the foundation of Spring Boot development.

---

### 05 — Practical Application

**Objective:** Apply the concepts learned throughout this level by building a Java application that interacts with a relational database.

**Suggested Project: Inventory Management System**

**Functional Requirements**

- Manage products.
- Manage categories.
- Add, update, and delete records.
- Retrieve and search products.
- Manage stock quantities.
- Handle database operations.

**Technical Requirements**

- Design a relational database.
- Write SQL queries.
- Connect to the database using JDBC.
- Implement ORM using Hibernate.
- Map entities and relationships.
- Understand the role of Spring IoC and Dependency Injection.
- Organize application components using Spring Core.

> **Goal:** Understand how Java applications interact with databases and how Spring manages application components and dependencies.

---

### 06 — Recommended Books

This section is reserved for books and additional learning references that will be uploaded to the repository.

| Resource | Notes |
|---|---|
| Database Books | To be added |
| SQL References | To be added |
| JDBC Books | To be added |
| Hibernate & JPA Books | To be added |
| Spring Framework Books | To be added |

---

## COMPLETION CHECKLIST

Before moving to the next level, make sure you can:

### Database & SQL
- [ ] Understand relational database concepts.
- [ ] Design database schemas and ER diagrams.
- [ ] Write SQL queries and perform CRUD operations.
- [ ] Understand Joins, Subqueries, and CTEs.
- [ ] Understand Normalization, Indexes, and Transactions.

### JDBC
- [ ] Explain JDBC architecture.
- [ ] Establish database connections using JDBC.
- [ ] Use Statement and PreparedStatement.
- [ ] Perform CRUD operations.
- [ ] Manage database transactions.
- [ ] Understand the DAO Pattern.

### JPA & Hibernate
- [ ] Explain ORM, JPA, and Hibernate.
- [ ] Map Java entities to database tables.
- [ ] Understand the entity lifecycle.
- [ ] Implement entity relationships.
- [ ] Understand Cascade and Fetch Types.
- [ ] Write basic JPQL queries.
- [ ] Understand the Persistence Context.

### Spring Framework Core
- [ ] Explain Inversion of Control.
- [ ] Understand Dependency Injection.
- [ ] Work with Spring Beans.
- [ ] Understand ApplicationContext.
- [ ] Configure Spring using annotations.
- [ ] Understand Bean Scopes and Lifecycle.
- [ ] Create and manage dependencies using Spring Core.

### Practical Experience
- [ ] Complete the suggested practical project.
- [ ] Apply database and persistence concepts.
- [ ] Organize application components using Spring Core.
- [ ] Upload your project to GitHub.
- [ ] Explain your implementation and design decisions.

---

## WHAT'S NEXT?

<div align="center">

### CONGRATULATIONS!

You have completed the Intermediate Level and built a solid understanding of databases, Java persistence technologies, and the Spring Framework Core.

You are now ready to take the next step toward building professional backend applications using Spring Boot.

### CONTINUE YOUR JOURNEY

[**GO TO ADVANCED LEVEL →**](../Advanced/README.md)

[← Back to Main Roadmap](../README.md)

---

**SPRING BOOT BACKEND ROADMAP**

*Learn • Build • Practice • Improve*

</div>

