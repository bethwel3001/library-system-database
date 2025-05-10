# 📚 Library Management System

A structured and normalized MySQL database project to manage the operations of a typical library — including books, authors, categories, members, and borrowing records.

---
[![ERD](erd/library%20system%20database.png)](https://dbdiagram.io/d/library-system-database-681f3a035b2fc4582f02ba20)
---

## 📝 Description

This project is a complete database solution designed using only MySQL (SQL script-based). It includes all key database features:

- **Authors** who write books
- **Books** with ISBN, availability, and linked categories
- **Categories** that group books (many-to-many)
- **Members** who borrow books
- **Loans** tracking book borrow and return details
- Enforced **Primary Keys**, **Foreign Keys**, and relational integrity
- Support for **1-to-Many** and **Many-to-Many** relationships

---

## ⚙️ How to Run / Setup

### ✅ Requirements
- MySQL server (v5.7+ recommended)
- MySQL Workbench or MySQL CLI

### 📂 Steps

1. Download or clone the project folder.
2. Open a terminal in the folder and run:
   ```bash
   mysql -u <your_username> -p < library_management.sql
   ```
3. OR import via MySQL Workbench:
   - Open library_management.sql
   - Select your connection and click Run (▶️)

   The script will:
- Create the database library_management
- Create and configure all tables, constraints, and relationships

## 📜 License
MIT License © 2025