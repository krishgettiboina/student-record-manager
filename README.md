# student-record-manager
# Student Record Manager (Java)

A console application to manage student records: add, view, search, update and delete.

## Problem Statement
Keeping student details on paper or in scattered files is slow and error-prone. This program stores records in one place and lets you manage them from a simple menu.

## Features
- Add a student (roll number, name, marks)
- View all students
- Search by roll number
- Update name and marks
- Delete a record
- Input validation (no duplicate roll numbers, marks between 0 and 100, no crash on wrong input)

## Concepts Used
- Classes and objects, encapsulation (private fields with getters and setters)
- `ArrayList` collection
- Loops, `switch` and methods
- Exception handling (`NumberFormatException`)

## How to Run
1. Install JDK 8 or later.
2. Save `StudentRecordManager.java` in a folder.
3. Compile: `javac StudentRecordManager.java`
4. Run: `java StudentRecordManager`

## Sample Output
Add your own screenshot here, for example `screenshot.png`.

## Limitations and Future Work
- Data is lost when the program closes. Next step: save records to a file.
- Add sorting by marks and a simple GUI.

## Author
Jaikrish Gettiboina, SY BTech CSE (AI & ML), JSPM University, Pune
