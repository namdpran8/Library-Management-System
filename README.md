# 📚 Library Management System (Python)

<p align="center">
  🚀 A complete Command-Line Library Management System built using Python with JSON-based storage.
</p>

---

## 🔗 Live Repository

👉 https://github.com/priyam-10/Library-Management-System

---

## 📌 Overview

This project is a **CLI-based Library Management System** designed to simulate real-world library operations such as user management, book inventory handling, and transaction processing.

It demonstrates core programming concepts like:
- Object-Oriented Programming (OOP)
- File Handling
- Data Persistence using JSON

---

## ✨ Key Features

### 👤 User Module
- Create account with validation
- Secure login using Account ID & PIN
- View personal details
- Update profile (name, phone, PIN)

### 📚 Book Module
- View available books
- Issue book (only one at a time)
- Return issued book
- Real-time quantity update

### 🔐 Admin Module
- Admin authentication system
- Add new books
- Update book quantity
- View full book inventory

---

## 🛠️ Tech Stack

| Category        | Technology |
|----------------|-----------|
| Language       | 🐍 Python |
| Data Storage   | 📂 JSON Files |
| Concepts Used  | 🧠 OOP, File Handling |

---

## 📂 Project Structure

Library-Management-System/
│
├── main.py # Main application logic
├── data.json # Stores user data
├── book.json # Stores book records
└── README.md # Project documentation

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/priyam-10/Library-Management-System.git
cd Library-Management-System
```

### 2️⃣ Run the Project

```bash
python main.py
```

## 🧠 System Workflow

User → Create Account → Login → Access Features
                          ↓
          ┌───────────────┼───────────────┐
          ↓               ↓               ↓
     View Details     Issue Book     Return Book
                          ↓
                   Update Database (JSON)

---

## 🔍 Validation & Constraints

- Age must be greater than 14  
- Mobile number must be 10 digits  
- PIN must be exactly 4 digits  
- Only one book can be issued at a time  

---

## ⚠️ Limitations

- CLI-based (no GUI)  
- No database (uses JSON only)  
- Single-user session (no concurrency)  

---

## 🚀 Future Enhancements

- 🎨 GUI using Tkinter  
- 🌐 Web version using Flask/Django  
- 🗄️ Database integration (MySQL/MongoDB)  
- 🔐 Password encryption  
- 📊 Dashboard for analytics  

---

## 📈 Learning Outcomes

This project helped in understanding:

- Real-world system design basics  
- Data storage using JSON  
- Structuring Python applications  
- Handling user input and validation  

---

## 👨‍💻 Author

**Priyam Singh**

---

## ⭐ Support & Contribution

If you found this useful:

- ⭐ Star the repository  
- 🍴 Fork the project  
- 🛠️ Contribute improvements  
