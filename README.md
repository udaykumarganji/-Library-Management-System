
# Library Management System – SQL Schema

## 📌 Overview
This project involves designing a database schema for a library using SQL and ER diagrams. It is a part of the SQL Developer 

## 🧱 Tables Created
1. **Authors** – Stores author info.
2. **Categories** – Stores book genres.
3. **Books** – Stores book info linked to authors and categories.
4. **Members** – Library members who borrow books.
5. **IssuedBooks** – Logs when books are issued and returned.

## 🔗 Relationships
- One author can write many books
- One category contains many books
- One book can be issued many times
- One member can issue many books

## 🛠 Tools Used
- MySQL Workbench (for schema)
- dbdiagram.io (for ER diagram)
- GitHub (for version control)

## 📂 Files in Repo
- `schema.sql` – SQL commands to create all tables
- `ER-Diagram.png` – The ER diagram of the schema
- `README.md` – This file

## 🚀 How to Use
1. Open `schema.sql` in MySQL Workbench
2. Run each statement to create the schema
3. Explore and expand based on your needs

