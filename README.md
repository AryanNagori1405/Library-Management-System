# Library Management System - Java

## Overview
This is a console-based Library Management System implemented in Java. The system allows librarians to manage books, track student registrations, and handle book check-ins/check-outs efficiently.

## Features
### Book Management
Add new books with details (Serial No, Name, Author, Quantity)

Search books by Serial Number or Author Name

Upgrade book quantity

Display all available books

Check-out and check-in books

### Student Management
Register new students

View all registered students

Borrow books (max 3 per student)

Return books

## Class Structure
book.java - Represents a single book with properties and constructor for input

books.java - Handles all book-related operations (add, search, display, etc.)

student.java - Represents a student with borrowing capacity

students.java - Manages student operations (registration, book transactions)

Library.java - Main class with menu-driven interface

### How to Run
Ensure you have Java JDK installed

Compile all Java files:
javac Library.java

Run the main class:
java Library

## Usage Instructions

### Main Menu Options:

1: Add new book

2: Upgrade book quantity

3: Search books (by Serial No or Author)

4: Show all books

5: Register student

6: Show all students

7: Check-out book

8: Check-in book

0: Exit

### System Constraints:

Maximum 50 books capacity

Maximum 50 students capacity

Students can borrow up to 3 books at a time

### Technical Details
Data Structures: Arrays for storing books and students

Input Handling: Scanner class for console input

Validation: Checks for duplicate books/students

State Management: Tracks available copies vs total copies

### Future Enhancements
Implement database persistence

Add due date tracking for borrowed books

Include fine calculation for late returns

Implement user authentication

Add GUI interface
