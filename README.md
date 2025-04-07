# PHP-CRUD-API  

![Programming Language](https://img.shields.io/badge/PHP-lavender?style=flat&logo=php&logoColor=white)

![Database](https://img.shields.io/badge/SQLite-blue?logo=sqlite&logoColor=white) ![Framework](https://img.shields.io/badge/PDO-gray?style=flat&logo=php&logoColor=white) 

![Platform: Web](https://img.shields.io/badge/Platform-Web-blue?logo=google-chrome)

![Last Commit](https://img.shields.io/github/last-commit/ander1code/php-crud-api?color=yellow&logo=github) 

---

## 1. Description
**PHP-CRUD-API** is an API developed using **PHP** with **PDO** connection to an **SQLite3 database**. This API features secure data handling and includes essential CRUD functionalities tailored for managing physical person records.

## 2. System Characteristics

### 2.1. Registration
- Enables physical person registration within the system.

### 2.2. Search
- Provides search functionality for physical persons by relevant attributes.

### 2.3. Login
- Includes user authentication with secure **SHA512 encryption** for login credentials.

## 3. Software and Tools Used

### Programming Language
- **PHP:** Version 7.3.23

### Database
- **SQLite 3:** Lightweight database for efficient data storage.
- **PDO:** PHP Data Objects for secure database connection and queries.

### Security Features
The system incorporates multiple layers of security to protect against vulnerabilities:
- **SQL Injection Protection:** Prevents unauthorized manipulation of SQL queries.
- **PHP Injection Protection:** Safeguards against malicious PHP code execution.
- **Cross-Site Scripting (XSS) Protection:** Secures user interactions against scripting attacks.
- **CSRF Protection:** Prevents Cross-Site Request Forgery attacks to secure user actions.

### Design Patterns
The API is designed with modern software engineering principles to ensure scalability and maintainability:
- **Singleton:** Ensures a single instance for managing core components.
- **Facade:** Simplifies complex subsystems for easy interaction.
- **Factory:** Handles object creation without specifying their concrete classes.
- **Abstract Factory:** Provides an interface for creating families of related objects.
- **Adapter:** Allows disparate systems to communicate seamlessly.

---
