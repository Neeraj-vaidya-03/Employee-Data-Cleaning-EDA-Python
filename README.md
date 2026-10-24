# 📊 Employee Dataset Analysis: Data Cleaning & EDA (Pandas & Matplotlib)

An end-to-end data cleaning and exploratory data analysis (EDA) project using **Python**, **Pandas**, and **Matplotlib**. This project demonstrates standard preprocessing workflows for raw dataset cleanup, feature inspection, anomaly detection, and data visualization.

---

## 🚀 Project Overview
In data analytics, real-world data requires structured cleaning and validation before modeling or dashboard creation. This project covers essential operations:
* Inspecting dataset dimensions, data types, and non-null counts.
* Standardizing column headers and handling data types.
* Analyzing distributions, group trends, and statistical outliers in employee compensation and demographics.

---

## 🛠️ Tech Stack
* **Language:** Python 3.11+
* **Libraries:** Pandas, Matplotlib, NumPy
* **Environment:** VS Code, Jupyter Notebook

---

## 📂 Key Data Cleaning & Analysis Steps

### 1. Data Profiling & Inspection
```python
import pandas as pd

# Load dataset and inspect structure
df = pd.read_csv('Employee Dataset.csv')
df.head()
df.info()
df.describe()
```

### 2. Preprocessing & Quality Checks
* Checked for missing values and duplicates (`isnull()`, `duplicated()`).
* Standardized column casing and whitespace formatting.
* Ensured accurate variable types (`age`, `salary`, `id`).

### 3. Exploratory Visualizations (Matplotlib)
* **Salary Distribution:** Histogram analysis to observe skewness and central tendencies.
* **Age vs. Salary:** Scatter plot identifying relationships between experience/age and compensation.
* **Group Comparisons:** Categorical aggregation to compare average salaries across segments.
* **Outlier Detection:** Box plot identification of extreme salary data points using IQR principles.

---

## 📁 Repository Structure
```text
├── Employee Dataset.csv     # Raw dataset file
├── Employee_Dataset.ipynb   # Jupyter Notebook with cleaning & EDA code
└── README.md                # Project documentation
```

---

## 👤 Author
* **Aspiring Data Analyst**  
* Focus Areas: Data Analytics | Python | SQL | Power BI
