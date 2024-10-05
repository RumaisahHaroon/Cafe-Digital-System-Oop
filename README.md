# Cafe-Digital-System-Oop
This was my Second Semester Project for Object Oriented Programming


## Overview

This project is a **Cafe Digital System** designed as part of my second semester-end project. It serves as a digital interface for managing cafe operations, allowing users to view the menu, place orders, and calculate bills. The system is implemented using **Object-Oriented Programming (OOP)** concepts in C++, such as classes, composition, inheritance, and more advanced principles of OOP.

## Features
- Display cafe menu with prices
- Take customer orders and calculate total cost
- Handle multiple orders in a single session
- Save and retrieve order history using file handling
- Basic user interaction with input validation



## OOP Concepts Used
- **Classes and Objects**: The core structure of the system is built using classes for menu items, orders, and the cafe itself.
- **Composition**: The `Order` class contains objects of the `MenuItem` class, representing a real-life relationship between orders and menu items.
- **Inheritance**: Specialized classes inherit from base classes to extend functionality, such as creating different types of menu items (e.g., beverages, food items).
- **Polymorphism**: Virtual functions are used for handling different types of items in a uniform way, allowing for dynamic method invocation.
- **Encapsulation**: Data members are kept private, accessed via public getter and setter methods to maintain data integrity.
- **Abstraction**: Complex operations like order processing and bill calculation are abstracted through methods, simplifying user interaction.
- **File Handling**: Orders and menu data are stored and retrieved from files to simulate data persistence.

  
## Technologies Used
- **C++**: Core programming language used for the project, with OOP principles.
