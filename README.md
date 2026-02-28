# 🗂️ CRUD Application using Java

## 📌 Project Overview
The CRUD Application is a Java-based program developed to perform basic database operations: **Create, Read, Update, and Delete** records.  
This project demonstrates practical implementation of **Core Java, JDBC, SQL, and Object-Oriented Programming (OOPS)** concepts.

The application connects to a relational database (MySQL) and performs data manipulation operations efficiently.

---

## 🚀 Technologies Used
- Java (Core Java)
- JDBC (Java Database Connectivity)
- MySQL
- SQL
- OOPS Concepts
- Eclipse / VS Code

---

## 🧠 OOPS Concepts Implemented
- Classes & Objects
- Encapsulation
- Abstraction
- Modular Code Structure
- Exception Handling

---

## ✨ Features
- ➕ Create new records
- 📄 Read / View records
- ✏️ Update existing records
- ❌ Delete records
- Database connectivity using JDBC
- Input validation and exception handling
- Menu-driven console interface

---

## 🗄️ Database Details

**Database Name:** crud_db  

### Example Table Structure

| Field      | Type        |
|------------|------------|
| id         | INT (PK)   |
| name       | VARCHAR    |
| email      | VARCHAR    |
| phone      | VARCHAR    |

---

## ⚙️ How to Run the Project

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/CRUD-Application-Java.git
   ```

2. Open the project in Eclipse / VS Code.

3. Create database in MySQL:
   ```
   CREATE DATABASE crud_db;
   ```

4. Create the required table as per schema.

5. Update JDBC connection details in the code:
   ```java
   String url = "jdbc:mysql://localhost:3306/crud_db";
   String username = "root";
   String password = "your_password";
   ```

6. Run the `Main.java` file.

---

## 📂 Project Structure
```
CRUD-Application/
│
├── src/
│   ├── model/
│   ├── dao/
│   ├── service/
│   └── Main.java
│
├── database/
│   └── crud_db.sql
│
└── README.md
```

---

## 🎯 Learning Outcomes
- Practical implementation of CRUD operations
- Hands-on experience with JDBC
- Understanding of database connectivity
- Writing modular and maintainable Java code
- Handling SQL exceptions and debugging issues

---

## 🔮 Future Enhancements
- Add GUI using JavaFX / Swing
- Add User Authentication
- Implement REST API using Spring Boot
- Add pagination and search functionality
