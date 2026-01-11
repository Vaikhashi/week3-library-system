# 📚 Console-Based Library Management System

## 📝 Project Description
The **Console-Based Library Management System** is a Java console application designed to manage basic library operations such as book tracking, member registration, and borrowing/returning books.  
It applies **Object-Oriented Programming (OOP)** principles and uses **file-based data persistence** to store data permanently.

This project is built as part of **Week 3 – Java Programming Basics** to strengthen understanding of Java fundamentals, OOP concepts, collections, and file handling.

---

## 🎯 Project Objectives
- Apply core **Java programming concepts**
- Implement **OOP principles** such as encapsulation and modular design
- Use **ArrayList** to manage collections
- Implement **File I/O** for data persistence
- Build a **menu-driven console application**
- Handle invalid inputs and errors gracefully

---

## ✨ Features
- Add, remove, and search for books
- Register and manage library members
- Borrow and return books with due dates
- Detect overdue books
- File-based data persistence using text files
- Input validation and exception handling
- Library statistics generation

---

## 🛠️ Technologies Used
- Java (JDK – Eclipse Adoptium)
- Object-Oriented Programming (OOP)
- File I/O (BufferedReader, FileWriter)
- Collections (ArrayList)
- VS Code

---

## ⚙️ Setup & Installation Instructions

### Prerequisites
- Java JDK installed (Eclipse Adoptium)
- VS Code or any Java-supported IDE

### Steps to Run the Project
```bash
# Compile the Java files
javac -d bin src/main/java/library/*.java

# Run the application
java -cp bin library.Main
week3-library-system/
│── src/
│   └── main/
│       └── java/
│           └── library/
│               ├── Main.java        # Entry point and menu system
│               ├── Book.java        # Book entity class
│               ├── Member.java      # Member entity class
│               ├── Library.java     # Core business logic
│               └── FileHandler.java # File I/O handling
│── data/
│   ├── books.txt                   # Stores book data
│   └── members.txt                 # Stores member data
│── README.md
│── .gitignore
