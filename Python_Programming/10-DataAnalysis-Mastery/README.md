# 📊 Module 10: Data Analysis with NumPy

> **"Turning Raw Data into Actionable Insights using High-Performance Numerical Computing."**

## 📌 Module Overview
This module marks my entry into the world of **Data Science and AI**. I shifted from standard Python lists to **NumPy (Numerical Python)**, the fundamental library for scientific computing. I focused on mastering N-dimensional arrays, vectorized operations, and statistical data normalization.

---

## 🏗️ Core NumPy Concepts

### 1. N-Dimensional Arrays (`ndarray`)
* **Efficiency:** Learned how NumPy arrays are stored in contiguous memory, making them significantly faster and more memory-efficient than Python lists.
* **Dimensions:** Mastered creating 1D, 2D (Matrices), and 3D arrays to represent complex data structures.
* **Attributes:** Used `.shape`, `.ndim`, `.size`, and `.dtype` to inspect and understand the structure of data in memory.



### 2. Array Engineering & Reshaping
* **Structural Changes:** Used `.reshape()` to change data dimensions (e.g., converting a 1D pixel array into a 2D image format).
* **Pre-defined Arrays:** Utilized `np.ones()` for weight initialization and `np.eye()` for creating identity matrices used in linear algebra.
* **Sequencing:** Generated precise data ranges using `np.arange()` for plotting and data sampling.

### 3. Vectorization & Universal Functions
* **Speed:** Replaced slow `for` loops with **Vectorized Operations**, allowing element-wise addition, subtraction, and multiplication to run at C-language speeds.
* **Mathematical Power:** Applied Universal Functions (ufuncs) like `np.sqrt()`, `np.exp()`, and `np.log()` across entire arrays instantly.



### 4. Data Slicing & Logical Filtering
* **Precision Extraction:** Mastered advanced slicing (`arr[1:, 1:3]`) to extract specific data chunks from large matrices.
* **Boolean Masking:** Implemented logical operations like `data[(data>=5) & (data<=8)]` to filter datasets based on specific criteria.

---

## 📊 Statistical Analysis & AI Pre-processing

* **Normalization:** Implemented data scaling using the formula `(data - mean) / std_dev` to ensure features have a mean of 0 and a standard deviation of 1.
* **Aggregations:** Used `np.mean()`, `np.median()`, `np.var()`, and `np.std()` to perform quick statistical summaries on massive datasets.

---

## 🛡️ Why NumPy for AI/ML?
* **Foundation:** NumPy is the base for libraries like Pandas, Scikit-Learn, and TensorFlow.
* **Image Processing:** Images are treated as NumPy arrays (Pixels), making array manipulation the first step in Computer Vision.
* **Performance:** Processing millions of rows of data is only possible in real-time due to NumPy’s optimized memory management.

---

## 👔 Interview Insights
* **NumPy vs Lists:** Lists store pointers to objects (Slow); NumPy stores raw data in contiguous blocks (Fast).
* **Vectorization:** It is the process of performing operations on entire arrays rather than individual elements, eliminating the overhead of Python loops.
