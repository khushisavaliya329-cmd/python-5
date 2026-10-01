[README (5).md](https://github.com/user-attachments/files/32891594/README.5.md)
# Python OOP Project: Employee Management System

A console-based **Employee Management System** built in Python using
**Object-Oriented Programming (OOP)** concepts.

## Project Overview

This project demonstrates how classes, inheritance, method overriding,
and object creation can be used to manage different types of people in
an employee system.

The program provides a menu-driven interface with these operations:

1.  Create a Person
2.  Create an Employee
3.  Create a Manager
4.  Show Details
5.  Exit

## OOP Concepts Used

### 1. Class and Object

The project defines `Person`, `Employee`, and `Manager` classes. Objects
are created from these classes to store individual records.

### 2. Inheritance

`Employee` inherits from `Person`, while `Manager` inherits from
`Employee`.

``` text
Person
  ↓
Employee
  ↓
Manager
```

### 3. `super()`

The child classes use `super()` to initialize attributes defined in
their parent classes.

### 4. Method Overriding

Each class has its own `show_details()` method. The child classes
override the method to display their additional information.

### 5. Encapsulation

Information such as name, age, employee ID, salary, and department is
stored as object attributes.

## Classes

### Person

Stores: - Name - Age

### Employee

Inherits from `Person` and adds: - Employee ID - Salary

### Manager

Inherits from `Employee` and adds: - Department

## How the Program Works

When the program starts, it displays the main menu.

### Create a Person

The user enters a name and age. A `Person` object is created and stored.

### Create an Employee

The user enters: - Name - Age - Employee ID - Salary

An `Employee` object is created and stored.

### Create a Manager

The user enters: - Name - Age - Employee ID - Salary - Department

A `Manager` object is created and stored.

### Show Details

The user can select Person, Employee, or Manager to display the details
of the corresponding stored record.

### Exit

Selecting option `5` exits the system and displays a goodbye message.

## How to Run

Make sure Python is installed on your computer.

Run the program using:

``` bash
python project.py
```

Then follow the menu shown in the terminal.

## Sample Output / Screenshots

### 1. Creating a Person and an Employee

![Screenshot 1](screenshot1.png)

### 2. Displaying Employee Details

![Screenshot 2](screenshot2.png)

### 3. Exiting the System

![Screenshot 3](screenshot3.png)

## Project Structure

``` text
Employee_Management_System/
│
├── project.py
├── README.md
├── screenshot1.png
├── screenshot2.png
└── screenshot3.png
```

## Technologies Used

-   **Python 3**
-   **Object-Oriented Programming (OOP)**
-   **Command-line / Console Interface**

## Author

**Khushi**
