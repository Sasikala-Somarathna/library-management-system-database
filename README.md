# library-management-system-database
MySQL database schema and sample data for a Library Management System.

# 📚 Library Management System Database

A complete MySQL database project for managing a library, including books, members, authors, categories, publishers, and borrowing records. This project demonstrates database design, normalization, foreign key relationships, and SQL operations.

---

## 🗂️ Database Name

`library_db`

---

## 📌 Project Features

📖 Manage books and book details
👥 Manage library members
✍️ Manage authors
🏷️ Manage book categories
🏢 Manage publishers
🔄 Track borrowing and returning of books
🔗 Maintain relationships using foreign keys
🧩 Demonstrate 3NF normalization
📊 Suitable for DBMS assignments and portfolio projects

---

## 🧱 Main Tables

| Table        | Description                         |
| ------------ | ----------------------------------- |
| `books`      | Stores book information             |
| `members`    | Stores member details               |
| `authors`    | Stores author details               |
| `categories` | Stores book categories              |
| `publishers` | Stores publisher information        |
| `borrowings` | Stores borrowing and return records |

---

## 🔗 Database Relationships

One author can write many books.
One category can contain many books.
One publisher can publish many books.
One member can borrow many books.
The borrowings table connects members and books.

---

## 🛠️ Technologies Used

MySQL
phpMyAdmin
SQL (DDL & DML)

---

## 🚀 How to Import the Database

### Using phpMyAdmin

1. Open phpMyAdmin
2. Create a new database named `library_db`
3. Click Import
4. Choose the file `library_db.sql`
5. Click Go

The database schema and sample data will be imported automatically.

---

## 📁 Repository Structure

```text
library-management-system-database/
│
├── library_db.sql
├── README.md
└── screenshots/
    ├── books-table.png
    ├── members-table.png
    └── borrowings-table.png
```

---


---

## 🎯 Learning Outcomes

This project demonstrates:

Database design principles
Entity–Relationship (ER) modeling
Primary and foreign keys
One-to-many relationships
SQL table creation
Data insertion and querying
Database normalization (up to 3NF)

---

## 👩‍💻 Author

Sasikala Somarathna
BICT Undergraduate
Faculty of Technology, Rajarata University of Sri Lanka

GitHub: https://github.com/
LinkedIn: https://www.linkedin.com/

---

## 📄 License

This project is for **educational and portfolio purposes**.
