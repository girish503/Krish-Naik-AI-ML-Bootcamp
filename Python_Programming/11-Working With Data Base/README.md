# 🗄️ Module 11: Persistent Data Systems (SQL & SQLite)

> **"Moving from Temporary RAM to Permanent Persistence: Architecting Scalable Relational Databases with SQL."**

## 📌 Module Overview
This module marks my transition from Data Analysis to **Backend Data Engineering**. While NumPy and Pandas handle data in memory (RAM), I have now mastered **SQLite** to manage data on disk. I focused on the "Serverless" architecture of SQLite and the power of Structured Query Language (SQL) to build high-performance data registries.

---

## 🏛️ 1. SQLite Architecture: The "Serverless" Logic
* **Zero Configuration:** Mastered the architecture where the entire database is a single disk file (`.db`), eliminating the need for a separate server process.
* **B-Tree Storage:** Learned how SQLite stores data in a B-Tree structure for lightning-fast retrieval, making it exponentially more efficient than scanning raw CSV files.
* **Embedded Power:** Implemented SQLite as an embedded engine—the same technology used in Android, iOS, and high-frequency trading logs.



---

## 🏗️ 2. SQL Mastery: The Language of Data
Mastered the core SQL syntax to perform complex operations on relational tables:
* **DDL (Data Definition Language):** Creating robust table schemas with defined data types like `INTEGER`, `TEXT`, and `REAL`.
* **DML (Data Manipulation Language):** Performing high-integrity **INSERT, UPDATE, and DELETE** operations.
* **DQL (Data Query Language):** Using `SELECT` statements with `WHERE` filtering and `ORDER BY` sorting to extract specific insights from large datasets.



---

## 🔌 3. The Python-to-SQL Bridge (`sqlite3`)
* **Connection Management:** Learned to establish secure bridges between Python scripts and the `.db` file using `sqlite3.connect()`.
* **The Cursor Protocol:** Mastered using the **Cursor** object—a specialized "Messenger" that executes SQL commands and fetches results back into Python structures.
* **Transaction Integrity:** Implemented `connection.commit()` to ensure data is safely written (Persistence) and `connection.close()` to prevent memory leaks.

---

## 🧪 4. Full-Stack Data Pipeline Integration
I have closed the loop by integrating the entire Module 10 and 11 stack:
1. **Store:** Save raw incoming data into **SQLite** relational tables.
2. **Retrieve:** Pull queried data into **Pandas** using `pd.read_sql_query()`.
3. **Analyze:** Scale and normalize numerical data using **NumPy**.
4. **Visualize:** Generate automated business dashboards using **Seaborn & Matplotlib**.



---

## 👔 Architect's Interview Insights
* **Serverless vs. Server-based:** SQLite is a library (no process overhead), while MySQL/PostgreSQL are services (network overhead). For lightweight AI tools and mobile apps, SQLite is the superior choice.
* **ACID Compliance:** SQLite ensures that every database transaction is **Atomic, Consistent, Isolated, and Durable**, which is mandatory for financial and banking software.
* **In-Memory Speed:** For HFT (High-Frequency Trading), SQLite can be run entirely in RAM for sub-millisecond response times.

---

### 🚀 Girish's Production Case Study
* **Database Files:** `sales_data.db`, `example.db`.
* **Workflow:** Built a system to ingest `sales_data.csv`, store it in a relational table, and perform SQL queries to identify top-performing regions instantly.
