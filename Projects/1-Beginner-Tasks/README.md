<div align="center">

# BEGINNER PROJECT

## Library Management System

**Apply Java fundamentals and Object-Oriented Programming in a console-based application.**

[← Projects Home](../README.md) • [Beginner Learning Guide](../../HELP/03-BEGINNER-GUIDE.md)

</div>

---

## 1. Project Overview

The **Library Management System** is a console-based Java application that helps manage books, library members, and borrowing operations.

The project is intended to demonstrate your understanding of Java fundamentals, Object-Oriented Programming, Core Java APIs, and basic software design practices.

The application should allow a user to manage the library's collection, register members, borrow available books, and process returned books.

## 2. Problem Statement

Small libraries need a simple way to keep track of their books and members. Managing this information manually can lead to duplicated records, inaccurate availability information, and difficulty tracking borrowed books.

The purpose of this project is to build a simple application that organizes library operations and applies the programming concepts covered in the Beginner Level.

## 3. Project Objectives

By completing this project, you should demonstrate the ability to:

- Design classes and objects to represent real-world entities.
- Apply encapsulation, inheritance, polymorphism, and abstraction where appropriate.
- Organize application logic into clear methods and classes.
- Work with Java Collections to manage application data.
- Handle invalid input and application errors.
- Search, filter, and sort collections.
- Apply basic clean-code and SOLID principles.
- Write basic unit tests.

## 4. Project Scope

### Core Features

| Feature | Description |
|---|---|
| Book Management | Add, update, remove, and display books. |
| Member Management | Register, update, remove, and display library members. |
| Book Search | Search for books by title, author, or identifier. |
| Book Borrowing | Allow a member to borrow an available book. |
| Book Returns | Register returned books and update their availability. |
| Borrowing Records | Keep track of active and previous borrowing records. |
| Availability | Display whether a book is available or currently borrowed. |

### Optional Enhancements

- Search by multiple criteria.
- Sort books by title or publication year.
- Limit the number of active loans per member.
- Add borrowing due dates.
- Save and load data using Java file handling.
- Add basic reporting, such as the most borrowed books.

## 5. Technical Requirements

| Area | Expected Technologies / Concepts |
|---|---|
| Programming Language | Java |
| Development Environment | JDK and IntelliJ IDEA |
| Build Tool | Maven |
| Object-Oriented Design | Classes, Objects, Interfaces, Inheritance, Polymorphism |
| Data Management | Collections Framework and Generics |
| Error Handling | Exception Handling and Custom Exceptions |
| Data Processing | Lambda Expressions and Stream API |
| File Operations | Java I/O (optional enhancement) |
| Testing | JUnit 5 fundamentals |

**Application Type:** Console-based Java application.

**Data Storage:** In-memory collections for the basic version. File-based persistence can be added as an enhancement.

**Out of Scope:** Databases, JDBC, Hibernate, Spring Framework, Spring Boot, and REST APIs are not required for this project.

## 6. Suggested Domain Model

The project may include the following main classes:

| Class | Responsibility |
|---|---|
| `Book` | Represents a book and its information. |
| `Member` | Represents a registered library member. |
| `Loan` | Represents a book borrowing record. |
| `Library` | Represents the library and its managed resources. |
| `BookService` | Contains book-related business operations. |
| `MemberService` | Contains member-related business operations. |
| `LoanService` | Handles borrowing and returning operations. |

You may introduce interfaces, abstract classes, enums, and additional classes when they improve the design.

### Main Relationships

- A member can have multiple borrowing records.
- A book can have multiple borrowing records over time.
- Each active borrowing record refers to one member and one book.

## 7. Business Rules

The application should enforce rules such as:

- Every book must have a unique identifier.
- Every member must have a unique identifier.
- A member cannot borrow a book that is unavailable.
- A book cannot be returned unless it is currently borrowed.
- Invalid or missing information must be handled appropriately.
- Borrowing records must remain consistent with book availability.

You may introduce additional rules and document your assumptions.

## 8. Suggested Application Structure

A simple package organization could look like this:

```text
library-management-system/
├── src/
│   ├── main/
│   │   └── java/
│   │       └── com/example/library/
│   │           ├── model/
│   │           ├── service/
│   │           ├── exception/
│   │           ├── util/
│   │           └── Main.java
│   └── test/
├── README.md
└── pom.xml
```

This structure is a starting point, not a mandatory design. Keep the application understandable and avoid unnecessary complexity.

## 9. Project Documentation

Your project documentation should explain the application and the decisions behind its implementation.

Recommended documentation:

| Document | Expected Content |
|---|---|
| Project Overview | Purpose, problem statement, objectives, and scope. |
| Requirements | Functional and non-functional requirements. |
| Use Cases | Main actors and interactions with the system. |
| Class Diagram | Main classes, attributes, operations, and relationships. |
| Business Rules | Rules governing borrowing, returns, and data consistency. |
| Setup Guide | JDK, Maven, installation, and execution instructions. |
| User Guide | How to use the console application. |
| Testing Notes | Important test cases and expected results. |

## 10. Expected Outcome

The final result should be a working console-based Library Management System with organized Java code, correct business behavior, and clear documentation.

The project should demonstrate that you can use Java and OOP concepts to model and solve a practical problem without relying on a framework.

---

<div align="center">

**BEGINNER LEVEL • BUILD YOUR JAVA FOUNDATION**

[← Projects Home](../README.md) • [Beginner Roadmap](../../Beginner/README.md)

</div>
