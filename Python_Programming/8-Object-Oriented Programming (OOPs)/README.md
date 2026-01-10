# 🏛️ Module 8: Object-Oriented Programming (OOP)

> **"From Scripts to Systems: Building Scalable and Maintainable Architecture."**

## 📌 Module Overview
This module documents my journey from writing simple functional scripts to mastering the **Core Pillars of Product Engineering**. I focused on building robust, maintainable, and reusable systems by understanding how data and logic interact in production-grade environments.

---

## 🏗️ The 4 Pillars of My Learning

### 1. Classes & Objects (The Blueprint vs. The Reality)
* **Custom Data Types:** Defined classes as blueprints to bind data and behavior into a single unit.
* **State Management:** Used instance variables and `self` as the "identity card" to manage unique object data in RAM.
* **The Constructor:** Implemented `__init__` to ensure every object starts with a valid "State".
* **File:** `8.1-oops.ipynb`.

### 2. Inheritance (Scaling the System)
* **Code Reusability:** Leveraged inheritance to build upon existing logic without rewriting code (DRY Principle).
* **Single vs. Multiple:** Mastered Multiple Inheritance and Python’s **MRO (Method Resolution Order)** via C3 Linearization—a power not available in strict languages like Java.
* **The Super Link:** Used `super().__init__` to bridge attributes between parent and child classes seamlessly.
* **File:** `8.2-inheritance.ipynb`.

### 3. Encapsulation (Data Integrity & Security)
* **Access Modifiers:** Implemented Public, Protected (`_`), and Private (`__`) variables to restrict unauthorized data access.

* **Getters & Setters:** Created controlled access points for data to perform **Validation Checks** (e.g., preventing negative values for age or balance) before updating the object state.
* **Name Mangling:** Explored how Python internally renames private attributes to prevent accidental interference.
* **File:** `8.4-Encapsulation.ipynb`.

### 4. Abstraction (Designing the Contract)
* **Hiding Complexity:** Focused on showing "What" an object does rather than "How" it does it to reduce system complexity.
* **Abstract Base Classes (ABC):** Used the `abc` module to define mandatory protocols that child classes **must** implement.

* **Architecture Security:** Ensured that incomplete classes cannot be instantiated, protecting the system from logical design errors.
* **File:** `8.5-Abstraction.ipynb`.

---

## ⚡ Advanced Concepts: Magic Methods & Operator Overloading

### 🔮 Magic (Dunder) Methods
* **Internal Hooks:** Overrode special methods like `__init__`, `__str__`, and `__repr__` to define how objects behave with built-in Python functions.
* **User vs. Developer View:** * `__str__`: Informal string representation for end-users.
    * `__repr__`: Formal/Technical representation for developer debugging.
* **Object Introspection:** Used `dir()` and `__dict__` to explore the internal namespace and mapping of attributes.
* **File:** `8.6-magicmethods.ipynb`.

### ➕ Operator Overloading
* **Syntactic Sugar:** Redefined the behavior of standard operators (`+`, `-`, `*`, `==`) for custom objects to make the API more "Pythonic".

* **Mathematical Objects:** Implemented `__add__`, `__sub__`, and `__mul__` for **Vector** and **Complex Number** classes to handle complex coordinate and algebraic logic.
* **Comparison Logic:** Used `__eq__` and `__lt__` to allow objects to be compared based on their internal values rather than memory addresses.
* **File:** `8.7-OperatorOverloading.ipynb`.

---

## 🛡️ Architect’s Interview Insights
* **Encapsulation vs. Abstraction:** Encapsulation hides **Data** for security; Abstraction hides **Complexity** for simplicity.
* **The "Secret" of MRO:** Python searches for methods from Left-to-Right in the inheritance list to resolve the "Diamond Problem".
* **Java vs. Python:** Python trusts the developer with Multiple Inheritance, while Java enforces safety through Interfaces. Python achieves "Interface-like" behavior using pure Abstract Base Classes.
* **Duck Typing:** "If it walks like a duck and quacks like a duck, it's a duck"—Python prioritizes object behavior (methods) over its class type.

---
