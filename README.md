# Student-Management-System-
A console-based student record management system built using Python and MySQL with OOP concepts
Technologies Used

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Core programming language |
| MySQL | Database management |
| MySQL Connector | Python-MySQL connectivity |
| OOP Concepts | Code structure and design |

---

## 📋 Features

- ✅ Add new student records
- ✅ View all student records
- ✅ Update existing student records
- ✅ Delete student records
- ✅ Search student by ID or name
- ✅ Secure database connectivity
- ✅ Data integrity and validation
- ✅ Clean modular code using OOP

---

## 🧠 OOP Concepts Applied

- **Encapsulation** — Student data and methods are wrapped inside classes
- **Inheritance** — Base class reused for extended functionality
- **Abstraction** — Complex database logic hidden from main program
- **Polymorphism** — Methods behave differently based on input

---

## 📁 Project Structure
Student-Management-System/
│
├── main.py          # Main program entry point
├── student.py       # Student class definition
├── database.py      # Database connection and queries
└── README.md        # Project documentation
---

## ⚙️ How to Run

### Prerequisites
- Python 3.x installed
- MySQL installed and running
- MySQL Connector for Python

### Installation Steps

**Step 1 — Install MySQL Connector**
pip install mysql-connector-python
**Step 2 — Set up the Database**
- Open MySQL
- Create a database called `student_db`
- Run the following SQL:
```sql
CREATE DATABASE student_db;
USE student_db;
CREATE TABLE students (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100),
    age INT,
    course VARCHAR(100),
    email VARCHAR(100)
);
Step 3 — Update Database Credentials
Open database.py
Update your MySQL username and password
Step 4 — Run the Program
python main.py

📊 Sample Output
====== Student Management System ======
1. Add Student
2. View All Students
3. Update Student
4. Delete Student
5. Search Student
6. Exit
Enter your choice:

🎯 Learning Outcomes
Hands-on experience with Python and MySQL integration
Applied OOP principles in a real-world project
Understood CRUD operations and database management
Improved problem-solving and debugging skills

👩‍💻 Developer
Ravikala
BCA Graduate — Bhandarkars Arts and Science College, Mangalore University 2026
📧 ravikalashetty411@gmail.com
🔗 LinkedIn:https://www.linkedin.com/in/ravikalashetty0110
