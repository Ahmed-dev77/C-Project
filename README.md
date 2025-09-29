# C++ Project
The Student Report Card Management System is a C++ console project. It stores student details like roll number, name, and marks in 5 subjects. The system calculates percentage and grade automatically. Users can create, view, update, search, and delete student records. All records are saved in a binary file for future access.
# 🎓 Student Report Card Management System (C++)

The **Student Report Card Management System** is a simple console-based application written in **C++**.  
It is designed to store, manage, and display student academic records using **object-oriented programming (OOP)** and **file handling** concepts.  
This project demonstrates how to handle data persistence with binary files and provides a beginner-friendly example of a real-world application.

---

## ✨ Features
- ➕ **Add Student Record** – Enter roll number, name, and marks for 5 subjects.  
- 📄 **Display Records** – View all student records stored in the system.  
- 🔍 **Search by Roll Number** – Generate a detailed report card for one student.  
- ✏️ **Modify Record** – Update details of an existing student.  
- ❌ **Delete Record** – Remove a student’s data permanently.  
- 📊 **Class Results** – Display all students’ results in a tabular format with percentage and grade.  

---

## 🛠 Technologies Used
- **C++**  
- **Object-Oriented Programming (OOP)** – classes, objects, encapsulation  
- **File Handling** – binary file read/write (`student.dat`)  
- **Console I/O** – menu-driven interface  

---

## 📂 Project Structure
- `student` class → Stores student information, calculates percentage and grade.  
- `write_student()` → Adds new student record to file.  
- `display_all()` → Shows all records from file.  
- `display_sp(int)` → Displays a single student report card.  
- `modify_student(int)` → Updates existing student details.  
- `delete_student(int)` → Removes a student record.  
- `class_result()` → Prints all results in tabular form.  
- `result()` and `entry_menu()` → Menus for navigation.  

---

## 🚀 How to Run
1. Save the code as `student_report.cpp`.  
2. Compile with:  
   ```bash
   g++ student_report.cpp -o student_report
   ./student_report
