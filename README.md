# C++ Library Management System

This is a complete C++ project for my 3rd Semester OOP syllabus. It's a command-line application that simulates a real library's management system.

## Features

* Add new books and members (including different member types like Students).
* Issue and return books.
* Find books and members by ID.
* Polymorphic display for all items and members.
* All data is saved to `items.csv` and `members.csv` files and loaded on startup.

## How to Compile and Run

1.  Make sure you have a C++ compiler (like g++ or MinGW) installed.
2.  Navigate to the project folder in your terminal.
3.  Run the compile command:
    ```bash
    g++ *.cpp -o Pro
    ```
4.  Run the program:
    ```bash
    ./Pro
    ```

## OOP Syllabus Topics Covered

This project was built to demonstrate all key OOP concepts, including:

* Classes and Objects
* Inheritance (Single, Multilevel, and Multiple)
* Polymorphism (Virtual Functions, Dynamic Binding)
* Abstract Base Classes
* Multiple Inheritance (using `virtual` base classes to solve the Diamond Problem)
* Operator Overloading (for `<<`)
* Friend Functions
* Exception Handling (`try`/`catch`)
* File Handling (`fstream`)
* Templates (for the generic `findByID` function)
* Structs (for `Transaction`)
* Static members (for `Member::nextID`)
