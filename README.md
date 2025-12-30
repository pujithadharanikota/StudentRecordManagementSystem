# 🎓 Student Record Management System (Java Console Application)

A simple and complete **console-based Java application** for managing student records. This project showcases **core Java concepts** like Object-Oriented Programming (OOP), File Handling, Collections, and Input Validation.

## 🚀 Features

- ✅ Add new student records
- 🔍 Search students by **roll number**
- 📝 Update existing student information
- ❌ Delete student entries
- 📋 View all student records
- 📚 Sort students alphabetically by name
- 💾 Save data to file and load on startup
- 🔢 Accepts **alphanumeric roll numbers** like `22P31A0511`

## 🧠 Concepts Used

- Java Classes and Objects
- Encapsulation
- File I/O (`BufferedWriter`, `BufferedReader`)
- `ArrayList` for dynamic storage
- Input validation (name format, age limits)
- Menu-driven interface using loops and switch-case

---

## 🛠 Technologies

- Java 17+
- Console (Command Line)
- No external libraries required

---

## 📂 Folder Structure
StudentRecordSystem/
├── Student.java # Model class
├── StudentRecordSystem.java # Main logic + menu UI
└── students.txt # Auto-created file to store student data

## sample output
--- Student Record Management ---
1. Add Student
2. View All Students
3. Search by Roll No
4. Update Student
5. Delete Student
6. Sort by Name
7. Save to File
8. Exit
Choice: 1

Enter Roll No: 22P31A0511
Enter Name: Harini
Enter Age: 20
✅ Student added.

🔐 Validations
✔️ Name must contain only alphabets and spaces

✔️ Age should be between 5 and 100

✔️ Roll number must be unique
