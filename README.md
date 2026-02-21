# University Registration System

## 📌 Overview
This is a **Java-based University Registration System** that allows managing students, courses, and enrollments using **linked lists**.  
It simulates a university environment where administrators can add/remove students and courses, enroll students in courses, and track enrollment limits. The system also supports **undo and redo** actions for enrollment changes.

---

## ⚡ Features

- **Add/Remove Students:** Easily add new students or remove existing ones from the system.
- **Add/Remove Courses:** Create new courses or remove existing courses from the system.
- **Enroll Students:** Register students in courses with a maximum of **7 courses per student** and **30 students per course**.
- **Remove Enrollment:** Drop a student from a specific course.
- **List Courses by Student:** View all courses a student is enrolled in.
- **List Students by Course:** View all students enrolled in a specific course.
- **Undo/Redo Actions:** Undo or redo the last enrollment or removal action.
- **Sorting:** Courses for a student and students for a course are automatically sorted by ID upon enrollment.
- **Get Last Added:** Retrieve the last added student or course ID.

---

## 🛠️ Technologies Used

- **Java**
- **Linked Lists:** Custom implementation for students, courses, and enrollments.
- **Stack:** To implement undo/redo functionality.
- **Console-based Interface**

---

## 📋 How It Works

1. Run the `Project` class.
2. A console menu will appear with options to manage students, courses, and enrollments:


Add student

Add course

Remove student

Remove course

Enroll student in a course

Remove Enrollment

List courses by student

List students by course

Get last student added

Get last course added

Is Normal Student

Is Full Course

Sort student by course ID

Sort course by student ID

UNDO

REDO

EXIT



## 💡 Notes

- A student can enroll in **a maximum of 7 courses**.
- A course can have **up to 30 students**.
- Undo/Redo feature works only for enrollment/removal actions.
- Students and courses are uniquely identified by their **IDs**.

---
