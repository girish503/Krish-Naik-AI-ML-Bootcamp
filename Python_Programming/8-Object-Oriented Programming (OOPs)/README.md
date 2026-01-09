# 🏛️ Module 8: Object-Oriented Programming (OOP)

> **"From Scripts to Systems: Building Scalable and Maintainable Architecture."**

## 📌 Module Overview
This module documents my journey into the core of **Product Engineering**. I moved beyond simple functional scripts to master the four pillars of Object-Oriented Programming, focusing on how data and logic interact in production environments.

---

## 🏗️ The 4 Pillars of My Learning

### 1. Classes & Objects (The Blueprint vs. The Reality)
* **Custom Data Types:** Learned to define classes as custom types to bind data and behavior.
* **State Management:** Used instance variables and `self` to manage unique object identities in memory.
* **The Constructor:** Implemented `__init__` to ensure every object starts with a valid "State" (e.g., Bank Balance or Car Model).
* **File:** `8.1-oops.ipynb`.

### 2. Inheritance (Scaling the System)
* **Code Reusability:** Leveraged inheritance to build upon existing logic without rewriting code (DRY Principle).
* **Single vs. Multiple:** Mastered Single and Multiple Inheritance, understanding how Python uses **MRO (Method Resolution Order)** to resolve conflicts—a power not available in Java.
* **The Super Link:** Used `super().__init__` to bridge attributes between parent and child classes.
* **File:** `8.2-inheritance.ipynb`.

### 3. Polymorphism (One Interface, Many Behaviors)
* **Method Overriding:** Redefined parent methods in child classes to provide specialized behavior (e.g., Dog vs. Cat sounds).
* **Duck Typing:** Explored Python's dynamic nature where the presence of a method (e.g., `.area()`) is more important than the class type.
* **Functional Polymorphism:** Built a `print_area()` engine that processes different shapes (Circle, Rectangle) through a single function.
* **File:** `8.3-Polymorphism.ipynb`.

### 4. Abstraction (Defining the Contract)
* **Abstract Base Classes (ABC):** Used the `abc` module to define mandatory protocols that child classes **must** follow.
* **Architecture Security:** Ensured that incomplete classes cannot be instantiated, protecting the system from logic errors.

---

## 🛠️ Practical Product Models

### 💰 Bank Account Management
* **Logic:** Encapsulated balance management with validation logic for deposits and withdrawals.
* **Security:** Ensured data integrity by preventing direct access to sensitive balance variables.

### 📐 Geometric Shape Engine
* **Logic:** Built a hierarchy where a base `Shape` class dictates how `Rectangle` and `Circle` calculate area.
* **Scalability:** Demonstrated how new shapes can be added to the system without changing existing logic.

---

## 🛡️ Architect’s Interview Notes
* **MRO:** Python searches for methods from Left-to-Right in the inheritance list.
* **Self Identity:** `self` is a reference to the current instance of the class, acting as the object's ID card in RAM.
* **Java vs. Python:** Python trusts the developer with Multiple Inheritance through C3 Linearization, whereas Java enforces safety via Interfaces.

---
