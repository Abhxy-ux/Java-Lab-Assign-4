📘 Student Record Management System — Lab Assignment 4
📌 Description

This Java application manages student records using file handling and the Java Collections Framework. It loads data from students.txt, allows adding/searching/deleting students, sorts by marks, displays records using an Iterator, and saves updates back to the file. The program uses Comparator, BufferedReader, BufferedWriter, and RandomAccessFile to satisfy all assignment requirements.

🛠️ Features

Load records from file at startup

Add new students

Search students by name

Delete records by name

Sort by marks (descending)

Display all students using Iterator

Save updates back to file

Demonstrates RandomAccessFile

Uses ArrayList<StudentData> for record storage

📂 Project Files
File	Purpose
LabAssignment4.java	Main Java program
students.txt	Student data file (CSV)
▶ How to Run
javac LabAssignment4.java
java LabAssignment4

📄 Sample students.txt
101,Ankit,ankit@mail.com,B.Tech,85.5
102,Riya,riya@mail.com,M.Tech,91.0

🧾 Expected Output
Loaded students from file:
Roll No: 101
Name: Ankit
Email: ankit@mail.com
Course: B.Tech
Marks: 85.5
Roll No: 102
Name: Riya
Email: riya@mail.com
Course: M.Tech
Marks: 91.0
===== Capstone Student Menu =====
1. Add Student
2. View All Students
3. Search by Name
4. Delete by Name
5. Sort by Marks
6. Save and Exit
Enter choice: 1
Enter Roll No: 103
Enter Name: Karan
Enter Email: karan@mail.com
Enter Course: BCA
Enter Marks: 76.2
Sorted Student List by Marks:
Roll No: 102
Name: Riya
Email: riya@mail.com
Course: M.Tech
Marks: 91.0

📎 Notes

Place students.txt in the same directory as the Java file.

The program overwrites the file when saving.

Ensure CSV format is correct:
rollNo,name,email,course,marks
