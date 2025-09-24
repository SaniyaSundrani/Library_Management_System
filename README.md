# 📚 Library Management System (Java Swing + JDBC)

A desktop-based **Library Management System** built with **Java Swing** and **JDBC**.  
This project helps librarians and administrators manage books, students, and transactions such as issuing and returning books.

---

## 🚀 Features
- 👤 **Student Management** – Register and manage student records.
- 📖 **Book Management** – Add, view, and maintain library books.
- 🔑 **User Authentication** – Sign in to access the system securely.
- 📤 **Issue Book** – Track which student has borrowed which book.
- 📥 **Return Book** – Manage the return of borrowed books.
- 🏠 **Dashboard (Home)** – Centralized navigation for all library operations.

---

## 🛠️ Tech Stack
- **Language**: Java (Swing for GUI)
- **Database**: MySQL (via JDBC)
- **Build Tool**: Apache Ant (build.xml included)
- **IDE**: NetBeans (UI forms supported)

---

## 📂 Project Structure
```
src/
 ├── AddBook.java / AddBook.form
 ├── IssueBook.java / IssueBook.form
 ├── ReturnBook.java / ReturnBook.form
 ├── StudentRegistration.java / StudentRegistration.form
 ├── SignIn.java / SignIn.form
 ├── home.java / home.form
 ├── Connect.java   # Database connection utility
 └── img/           # Icons and images
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/SaniyaSundrani/Library-Management-System-Project.git
cd Library-Management-System-Project
```

### 2️⃣ Configure Database
- Install **MySQL** and create a database (e.g., `librarydb`).
- Update credentials in `Connect.java`:
```java
Connection con = DriverManager.getConnection("jdbc:mysql://localhost:3306/librarydb", "username", "password");
```

### 3️⃣ Build & Run
- Open the project in **NetBeans** (recommended) or any IDE supporting Ant.
- Build using:
```bash
ant compile
ant run
```

---


## 🤝 Contribution
Contributions are welcome!  
1. Fork the repo  
2. Create a new branch (`feature-xyz`)  
3. Commit changes  
4. Open a Pull Request  

---

## 📜 License
This project is licensed under the **MIT License**.

---

## 👨‍💻 Author
Developed by [Saniya Sundrani](https://github.com/SaniyaSundrani)