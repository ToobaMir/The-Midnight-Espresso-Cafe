# ☕ Cafe Management System (OOP Project in C++)

## Overview
This project is a **Cafe Management System** developed in **C++**.  
It demonstrates all four pillars of **Object-Oriented Programming (OOP)** in a real-world scenario, while keeping the code **concise, modular, and optimized**.  

---

## OOP Concepts Demonstrated
- **Abstraction** → `MenuItem` is an abstract base class with pure virtual methods (`display()`, `getPrice()`).
- **Encapsulation** → `FoodItem` and `BeverageItem` keep `name` and `price` as private members.
- **Inheritance** → `FoodItem` and `BeverageItem` inherit from `MenuItem`, while `Cashier` and `Customer` inherit from `Cafe`.
- **Polymorphism** → Virtual methods (`display()` and `getPrice()`) are overridden in derived classes.
- **Templates** → `Order<T>` class demonstrates the use of generic programming.
- **Static Members** → `Cafe::customerCount` tracks the total number of customers served.
- **Exception Handling** → The cafe throws an exception and closes automatically when the customer limit is reached.

---

## Features
- Display a cafe menu with beverages and food items.
- Place an order with multiple items.
- Cashier calculates **total, tax, and final bill**.
- Customer tracking using a **static counter**.
- Exception handling for customer limits.
- Modular and object-oriented code structure.

---
## Documentation
For a detailed explanation of the project, check out the **presentation slides**: 
https://drive.google.com/file/d/1gWYmQ3e3BXLHzy1MRFAJEyLcLW-309WW/view?usp=sharing 

