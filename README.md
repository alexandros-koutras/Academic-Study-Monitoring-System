# Academic-Study-Monitoring-System


---


## 💡 Overview

This repository contains an Object-Oriented Programming (OOP) project that implements an academic study monitoring system for a university department. The system is designed to manage the data and operations related to Students, Professors, and Courses, all coordinated by a Secretary class. The primary objective is to demonstrate strong OOP principles (Inheritance, Polymorphism) by creating a robust, class-based application that simulates the core functions of a university's student management system.


---


## 🛠️ Class Structure

- **Person Class** (Base Class): The fundamental class that acts as the parent for Student and Professor. It holds basic data like names, IDs, etc.
- **Student Class**: Inherits from Person. Manages student-specific data, including course enrollments, grades, academic semesters, and checking graduation status.
- **Professor Class**: Inherits from Person. Manages professor-specific data, including the courses they teach.
- **Course Class**: Manages course details, including mandatory/elective status, ECTS units, semester assignment, and the list of assigned professors.
- **Secretary Class**: The central management class. It holds lists of all Student, Professor, and Course objects and performs all transactional operations between them.


---


## ⚙️ Features

The application provides a console-based main menu allowing the user to manage the academic system:
- **CRUD Operations**: Create, Read, Update and Delete Professors, Students, and Courses.
- **Course Management**: Assigning professors to a specific course.
- **Enrollment**: Students can enroll in a course.
- **Grading and Reporting**: Displaying and saving a list of students who passed a specific course in a given semester. A Professor's ability to print semester statistics for all their courses. A Student's ability to print their analytic grades for the current and previous semesters.
- **Graduation Status**: Checking if a student meets the criteria for graduation (years of study, mandatory courses passed, required ECTS units).


---


## 🧰 Technologies Used

- **C Language**
- **Makefile** for build automation
- **Separate compilation** (headers + multiple `.c` files)


---


## 🧑‍💻 How to Build and Run

### 1. Clone the repository
git clone https://github.com/alexandros-koutras/Academic-Study-Monitoring-System
cd Academic-Study-Monitoring-System

### 2. Compile and run
make run


---


## 📂 Project Structure

Academic-Study-Monitoring-System/  
├── .vscode/
├── data/           # Initialising data for the system with premade proffesors, students and courses
├── include/        # Header files (.h) and definitions for the classes
├── modules/        # The implementation of the classes and the menu
├── main.cpp        # The main function
├── Makefile        # Build file for separate compilation
└── README.md       # Project documentation  
