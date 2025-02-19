# Library Management System

![SpringMVC](https://img.shields.io/badge/SpringMVC-4-green)
![HTML](https://img.shields.io/badge/HTML-5-red)
![CSS](https://img.shields.io/badge/CSS-3-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.0-purple)
![Postgresql](https://img.shields.io/badge/Postgresql-JPA-yellowgreen)

---

## 📖 What is the Library Management System?

The **Library Management System** is a web-based platform designed to streamline the management of library resources, providing an efficient and automated way for librarians and users to manage books, memberships, and transactions. 

The system supports two main user roles:
- **Librarians**: Manage books, issue/return records, and users.
- **Members**: Browse, borrow, and return books.

---

## 📌 Main Modules
1. **Librarian Module**
2. **Member Module**

---

## 🛠 Technologies Used
- **Backend**: Spring MVC, Hibernate, JPA
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Database**: PostgreSQL
- **Security**: Session-based authentication
- **Build Tool**: Maven
- **Version Control**: Git

---

## 🔍 Functional Requirements

### 📌 Librarian Module
- **Book Management**
  - Add, update, delete, and categorize books.
  - Maintain book stock availability.
- **Member Management**
  - Register and manage members.
  - Assign membership types (student, staff, guest, etc.).
- **Issue and Return Books**
  - Manage book lending process with due dates.
  - Generate fine for overdue books.
- **Reports and Analytics**
  - View reports on issued/returned books.
  - Track most borrowed books.

![Librarian Dashboard](https://via.placeholder.com/800x400.png?text=Librarian+Dashboard)

---

### 📌 Member Module
- **Book Search & Browsing**
  - Search books by title, author, or category.
  - Check book availability.
- **Borrowing & Returning Books**
  - Borrow available books.
  - View and track borrowed books with due dates.
- **Notifications & Alerts**
  - Receive alerts for due dates and new book arrivals.
- **Profile Management**
  - Update personal details and membership status.

![Member Dashboard](https://via.placeholder.com/800x400.png?text=Member+Dashboard)

---

## 📊 Database Schema
The system follows a structured relational database design with the following main tables:
- `books`: Stores book details (title, author, category, availability).
- `members`: Stores member details (name, contact, membership type).
- `transactions`: Tracks book borrow/return transactions.
- `fines`: Manages overdue fine records.

---

## 🔐 Security Features
- User authentication and role-based access control.
- Secure password storage with hashing.
- Session management to prevent unauthorized access.

---

## 🏁 Conclusion
The **Library Management System** offers an intuitive and efficient way for libraries to manage their resources, ensuring seamless book lending operations and member management. By leveraging **Spring MVC** and **PostgreSQL**, this project provides a robust and scalable platform for automating library functions.
