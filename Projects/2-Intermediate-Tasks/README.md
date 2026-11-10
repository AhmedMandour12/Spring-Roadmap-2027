<div align="center">

# INTERMEDIATE PROJECT

## Inventory Management System

**Apply database design, JDBC, Hibernate, JPA, and Spring Core in a structured Java application.**

[← Projects Home](../README.md) • [Intermediate Learning Guide](../../HELP/04-INTERMEDIATE-GUIDE.md)

</div>

---

## 1. Project Overview

The **Inventory Management System** is a Java application designed to manage products, categories, suppliers, and stock movements.

The project focuses on database-driven application development. It provides an opportunity to design a relational database, write SQL queries, connect Java to a database, use JDBC and ORM technologies, and manage application components using Spring Framework Core.

**Application Type:** Java application with a console-based interface or another lightweight interface of your choice.

## 2. Problem Statement

Businesses need to maintain accurate information about products and stock quantities. Managing inventory manually can result in inconsistent records, incorrect stock levels, and difficulty tracking incoming and outgoing products.

The purpose of this project is to create an application that stores inventory information in a relational database and provides reliable operations for managing products and stock movements.

## 3. Project Objectives

By completing this project, you should demonstrate the ability to:

- Design a relational database and represent it using an ER diagram.
- Write SQL queries for common and advanced data operations.
- Connect Java applications to databases using JDBC.
- Use PreparedStatement and manage database transactions.
- Map Java classes to database tables using JPA and Hibernate.
- Understand entity relationships and entity lifecycle.
- Organize application components using Spring Core.
- Apply dependency injection and separation of concerns.
- Compare direct JDBC access with ORM-based persistence.

## 4. Project Scope

### Core Features

| Feature | Description |
|---|---|
| Product Management | Add, update, delete, and view products. |
| Category Management | Organize products into categories. |
| Supplier Management | Maintain supplier information. |
| Stock Receiving | Record incoming stock quantities. |
| Stock Issuing | Record outgoing stock quantities. |
| Inventory Tracking | Display current stock for each product. |
| Product Search | Search by product name, SKU, or category. |
| Low Stock Report | Identify products whose quantities are below a defined threshold. |
| Stock Movement History | Review stock receipts and issues over time. |

### Optional Enhancements

- Product pagination and sorting.
- Stock valuation reports.
- Supplier-specific product reports.
- Export inventory reports to CSV.
- Search using multiple filters.
- Audit information such as creation and update timestamps.

## 5. Technical Requirements

| Area | Expected Technologies / Concepts |
|---|---|
| Programming Language | Java |
| Build Tool | Maven |
| Database | A relational database such as MySQL, Oracle, or PostgreSQL |
| Database Design | ERD, keys, constraints, normalization, indexes |
| SQL | DDL, DML, joins, subqueries, transactions |
| Database Connectivity | JDBC, PreparedStatement, ResultSet |
| ORM | JPA and Hibernate |
| Persistence | EntityManager and entity mapping |
| Dependency Management | Spring Framework Core |
| Configuration | Java-based or annotation-based Spring configuration |

**Important Scope Boundaries**

- JDBC and Hibernate/JPA should be treated as two persistence approaches that can be compared.
- You may implement separate persistence adapters behind common interfaces, or document and implement the approaches as separate versions.
- The project should not require Spring Boot, Spring MVC, Spring Data JPA, REST APIs, or Spring Security. These belong to the Advanced Level of this roadmap.

## 6. Suggested Domain Model

The project may include the following entities:

| Entity | Responsibility |
|---|---|
| `Product` | Stores product information and stock-related attributes. |
| `Category` | Groups related products. |
| `Supplier` | Stores supplier details. |
| `StockMovement` | Records stock receiving and issuing operations. |

### Main Relationships

- A category can contain multiple products.
- A product belongs to a category.
- A supplier may provide multiple products.
- A product can have multiple stock movement records.
- Each stock movement refers to a product and records a quantity and movement type.

The exact relationships can be adjusted according to your database design.

## 7. Business Rules

The application should enforce rules such as:

- Every product must have a unique SKU.
- Product quantities cannot be negative.
- A stock issue cannot exceed the available quantity.
- Every stock movement must reference an existing product.
- Stock receiving increases available quantity.
- Stock issuing decreases available quantity.
- Stock movement records should be retained for auditing.
- Database operations that update stock and movement records should be consistent and transactional.

## 8. Suggested Application Architecture

A layered design may be used:

```text
inventory-management-system/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/example/inventory/
│   │   │       ├── model/
│   │   │       ├── dao/
│   │   │       ├── repository/
│   │   │       ├── service/
│   │   │       ├── config/
│   │   │       └── Main.java
│   │   └── resources/
│   │       └── application.properties
│   └── test/
├── docs/
├── README.md
└── pom.xml
```

The persistence layer can be organized around interfaces, with JDBC and Hibernate/JPA implementations kept separate. Spring Core can manage the required objects and their dependencies.

## 9. Project Documentation

Your project documentation should describe the database design, persistence strategy, and application architecture.

Recommended documentation:

| Document | Expected Content |
|---|---|
| Project Overview | Problem statement, objectives, and scope. |
| Requirements | Functional and non-functional requirements. |
| Use Cases | Product, supplier, and inventory operations. |
| Database Design | ERD, tables, columns, keys, and constraints. |
| SQL Reference | Important queries, views, and database operations. |
| Persistence Design | JDBC and Hibernate/JPA implementation approach. |
| Entity Documentation | Entity mappings and relationship explanations. |
| Architecture | Layers, interfaces, implementations, and dependency flow. |
| Setup Guide | Database setup, configuration, Maven, and execution. |
| Testing Notes | Important scenarios and expected results. |

## 10. Expected Outcome

The final result should be a database-driven Inventory Management System with a clear relational schema, reliable stock operations, and organized Java code.

The implementation should demonstrate your understanding of SQL, JDBC, Hibernate/JPA, and Spring Core without introducing Spring Boot features before the Advanced Level.

---

<div align="center">

**INTERMEDIATE LEVEL • CONNECT JAVA TO DATA**

[← Projects Home](../README.md) • [Intermediate Roadmap](../../Intermediate/README.md)

</div>
