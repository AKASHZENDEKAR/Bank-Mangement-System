# 🏦 Bank Management System

A **Bank Management System** developed using **Java (Core Java + JDBC)** for backend operations and **HTML, CSS, and basic JavaScript** for the frontend.  
This project demonstrates core banking functionalities such as user registration, login, deposits, withdrawals, and balance management with database connectivity.

---

## 📌 Features

- User Registration
- User Login
- Deposit Money
- Withdraw Money
- Check Account Balance
- JDBC-based MySQL Database Connectivity
- Simple and clean user interface

---

## 🛠️ Technologies Used

### Backend
- Java (Core Java)
- JDBC
- MySQL

### Frontend
- HTML
- CSS
- JavaScript (Basic)

### Tools
- Git
- GitHub
- VS Code / IntelliJ IDEA / Eclipse
- MySQL Workbench

---
Bank-Mangement-System/
│
├── backend/
│ ├── dao/
│ ├── model/
│ ├── service/
│ ├── util/
│ └── Main.java
│
├── frontend/
│ ├── index.html
│ ├── login.html
│ ├── dashboard.html
│ ├── css/
│ └── js/
│
├── database/
│ └── bank.sql
│
└── README.md


---

## ⚙️ Prerequisites

- Java JDK 8 or above
- MySQL Server
- Git
- Any Java IDE (Eclipse / IntelliJ / VS Code)

---

## 🗄️ Database Setup

Run the following commands in MySQL:

```sql
CREATE DATABASE bank_management;
USE bank_management;

CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100),
    email VARCHAR(100) UNIQUE,
    password VARCHAR(50),
    balance DOUBLE DEFAULT 0
);

🔌 JDBC Configuration

Update database credentials in your Java JDBC utility file:

String url = "jdbc:mysql://localhost:3306/bank_management";
String user = "root";
String password = "your_password";


## 📂 Project Structure

Akash Zendekar
B.Tech – Information Science & Engineering

GitHub: https://github.com/AKASHZENDEKAR
