# 🏗️ OOP Java Problems (No Collections Allowed)

This repository contains **Object-Oriented Programming (OOP) problems in Java** where solutions are implemented **without using Collection APIs** (`ArrayList`, `HashMap`, etc.).  
Only **primitive arrays** and **custom classes** are used to demonstrate **OOP principles** like Encapsulation, Inheritance, Polymorphism, and Abstraction.

---

## 📌 Problem Statements (Attempt Any 5)

### 1. Custom Dynamic Array (Without ArrayList)
Design a class `MyArray` that mimics a **dynamic array** using primitive arrays internally.  
Features:  
- `add(int element)`  
- `get(int index)`  
- `size()`  
- `resize()` internally when the array gets full  

---

### 2. Inventory Management System
Classes: **Product, Warehouse, Order**  
Rules:  
- A product has `ID, name, price, quantity`  
- A warehouse holds a fixed-size array of products  
- An order requests products → must check stock before confirming  
*Restriction: No Collection types; only arrays/custom structures*

---

### 3. Banking System with OOP
Classes: **Bank, Account, Customer**  
Features:  
- Create new account  
- Deposit / Withdraw money  
- Print account statement  

**Inheritance:**  
- `SavingsAccount` → withdrawal limits  
- `CurrentAccount` → overdraft rules  

---

### 4. Car Simulation
Class: **Car** with properties → `speed, fuel, distanceTraveled`  
Methods:  
- `drive(int hours)` → updates distance and reduces fuel  

Subclass: **ElectricCar** → treats fuel as `battery percentage`  

*Demonstrates Inheritance & Polymorphism*

---

### 5. Shape Area Calculator
Base class: **Shape**  
Subclasses: **Circle, Rectangle, Triangle**  
Each implements `getArea()` and prints its type  

Concepts:  
- **Inheritance**  
- **Abstraction**  
- **Method overriding**

---

### 6. Employee Salary Calculation
Base class: **Employee**  
Subclasses: **FullTime, PartTime, Contractor**  
Each overrides `calculateSalary()`  

---

### 7. Matrix Operations (Without Collections)
Class: **Matrix**  
Supports:  
- Addition  
- Subtraction  
- Transposition  
- Multiplication  

*Restriction: Use only 2D arrays*

---

### 8. Custom Date Formatter
Class: **MyDate (day, month, year)**  
Methods:  
- Validate date  
- Increment by one day  
- Format as `dd-mm-yyyy`  

---

### 9. Student Grading System
Classes: **Student, Subject, ReportCard**  
- Student → `name, rollNumber, array of Subjects`  
- Subject → `name, marks`  
- ReportCard → `total, average, grade`  

*Restriction: No Collection APIs*

---

### 10. Basic ATM Machine Simulation
Classes: **ATM, UserAccount, Bank**  
Features:  
- PIN validation  
- Balance checking  
- Cash withdrawal  

*Restriction: Only arrays for storing accounts*

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Sai8094/Logical_Problems.git
   cd Logical_Problems
