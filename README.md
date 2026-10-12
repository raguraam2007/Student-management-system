# Student Management System

## About the Project

The Student Management System is a simple C++ project that helps manage student details through a console-based application. It makes it easy to add, view, search, update, and delete student records. The project uses file handling to save student information, so the data is still available when the program is run again.

## Features

* Add new student details
* View all student records
* Search for a student using their roll number
* Update student information
* Delete student records
* Save student details in a file

## Technologies Used

* C++
* File Handling
* Structures and Functions

## Student Details

The program stores each student's:

* Roll Number
* Name
* Department
* Marks

## How to Run

**1.** Install a C++ compiler, such as MinGW-w64.

**2.** Open the project folder in VS Code.

**3.** Open the terminal and compile the program:

```bash
g++ student_management.cpp -o student_management.exe
```

**4.** Run the application:

```powershell
.\student_management.exe
```

**5.** Select an option from the menu and follow the instructions displayed on the screen.

## Data Storage

Student records are saved in a file named `students.txt`. This allows the program to retain student details even after it is closed. Keep the file in the program's working directory when running the application again.

## What I Learned

While working on this project, I learned how to use structures and functions in C++, work with files, and perform basic operations on student records.

## Conclusion

This project helped me understand how C++ can be used to build a simple application for managing student information. It was also a good opportunity to practise file handling and menu-driven programming.
