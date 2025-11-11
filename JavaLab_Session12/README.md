# JavaLab_Session12

## 🎯 Problem Statement
Build a student record GUI using JavaFX with form controls and event handlers.

## 🌍 Real-World Scenario
Used in student enrollment or college record systems where user input is handled through a GUI.

## 🧠 Concepts Practiced
- JavaFX basics
- Event handling with lambdas
- GUI layout using GridPane and VBox
- MVC design principle
- ObservableList for dynamic updates

## 📘 Description
This project demonstrates a **Student Record System** built using **JavaFX**.
The user can:
- Input student ID, name, and course.
- Add new records to a live list.
- Clear all fields or reset the list.
- Get interactive alerts for success or input validation.

## ⚙️ How to Run
1. Ensure you have JavaFX installed.
2. Compile both `.java` files:
```bash
javac --module-path "path/to/javafx/lib" --add-modules javafx.controls Student.java StudentForm.java
