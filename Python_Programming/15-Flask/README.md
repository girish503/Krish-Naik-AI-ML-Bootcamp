# 🌐 Module 15: Web Architecture & RESTful API Development

> **"Bridging the Gap: Transforming Python Logic into Production-Grade Web Services and Scalable APIs."**

## 📌 Module Overview
This module marks my transition from standalone scripts to **Connected Systems**. I mastered the **Flask micro-framework** to expose Python business logic to the internet. I focused on the architectural flow between the Browser (Client), WSGI (Gateway), and Flask (Server), ensuring a robust separation between data processing and user interface.

---

## 🏗️ 1. Flask & Web Foundations
Implemented a professional web server architecture using the Flask framework.

* **WSGI Integration:** Developed applications on top of the **Web Server Gateway Interface (WSGI)**, enabling seamless communication between HTTP web servers and Python logic.
* **Dynamic Routing:** Mastered **Variable Rules** (`<int:score>`) to create data-driven URL endpoints, allowing a single route to handle millions of unique data inputs.
* **HTTP Methods:** Implemented secure data handling using **GET** for resource retrieval and **POST** for encrypted data submission via HTML forms.



---

## 🎨 2. Jinja2 Templating Engine
Mastered the **Jinja2** engine to achieve a clean **Separation of Concerns**, decoupling backend Python logic from frontend HTML design.

* **Expression Tags `{{ }}`:** Used to dynamically inject Python variables directly into HTML templates.
* **Control Structures `{% %}`:** Implemented complex frontend logic, including `if/else` conditionals for pass/fail status and `for` loops to iterate through data dictionaries.
* **Static File Management:** Leveraged `url_for` to dynamically link CSS and JavaScript files, ensuring path integrity across different deployment environments.



---

## 📡 3. RESTful API Architecture (JSON)
Engineered a language-agnostic **REST API** to serve raw data to modern web and mobile applications.

* **The CRUD Pattern:** Implemented the four golden pillars of API development:
    * **CREATE (POST):** Adding new resources to the system state.
    * **READ (GET):** Retrieving specific or bulk data using JSON serialization.
    * **UPDATE (PUT):** Modifying existing resources via ID-based lookups.
    * **DELETE (DELETE):** Permanently removing resources from the backend.
* **JSON Serialization:** Used `jsonify` to convert Python dictionaries into **JSON (JavaScript Object Notation)**, the universal language of the modern web.



---

## 👔 Architect's Production Insights
* **Separation of Concerns:** Never hardcode HTML strings in Python; always use `render_template` for UI and `jsonify` for Data.
* **REST vs. Web App:** Web apps return HTML for humans; REST APIs return JSON for other machines/software.
* **Security First:** Use **POST** for any action that modifies data or contains sensitive user information.

---

### 🚀 Girish's Full-Stack AI Infrastructure
My architectural stack now includes:
1. **Data Surgery:** NumPy & Pandas [Module 10].
2. **Persistence:** SQLite Relational Databases [Module 11].
3. **Observability:** Logging & Audit Trails [Module 12].
4. **Performance:** Multi-threading & Parallelism [Module 13].
5. **Memory:** Resource Optimization [Module 14].
6. **Interface:** Flask Web APIs & Jinja2 [Module 15].
