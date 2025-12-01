# Student Record Management Application

A simple Java console-based Student Record System demonstrating inheritance, OOP concepts, dynamic lists, and user interaction.
This application allows users to add student details, automatically calculate their grade, and display all saved records.

🔧 Features

Add student details (Roll No, Name, Course, Marks)

Auto-calculates grade based on marks

Display all stored student records

Uses inheritance (Student extends Person)

Stores multiple students using ArrayList

Simple menu-driven console interface

📚 Grade Criteria
Marks Range	Grade
≥ 90	A
≥ 75	B
≥ 60	C
< 60	D
▶️ How to Run

Compile the program:

javac StudentRecordApp.java


Run the application:

java StudentRecordApp

🧭 Menu Options

1 – Add Student

2 – Display All Students

3 – Exit Application

📝 Notes

The program uses an ArrayList to store student objects dynamically.

Grade is calculated automatically whenever marks are entered.

Inheritance is used:

Person → Base class

Student → Derived class extending Person
