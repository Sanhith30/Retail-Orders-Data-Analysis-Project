# 🛒 Retail Orders Data Analysis Project

A complete end-to-end data analysis and SQL integration project using Python and Microsoft SQL Server. This project demonstrates my ability to handle real-world datasets, perform data cleaning and transformation, derive business insights, and integrate Python with SQL Server for robust data operations.

---

##  Project Summary

This project focuses on analyzing a retail order dataset to extract meaningful insights for business decision-making. I processed raw CSV data, performed data cleaning, engineered new features, and integrated the processed dataset into a SQL Server database for further querying and analysis.

---

##  What I Did

### 🔹 Data Acquisition
- Used the Kaggle API to download the dataset: `ankitbansal06/retail-orders`.
- Unzipped and extracted the CSV file using Python's `zipfile` library.

### 🔹 Data Cleaning & Preprocessing
- Read the dataset using `pandas` and handled missing values by replacing `"Not Available"` and `"unknown"` with `NaN`.
- Renamed all column headers to lowercase and replaced spaces with underscores to maintain consistency and adhere to best practices.

### 🔹 Feature Engineering
- Derived a new column `profit` using the formula: `sale_price - cost_price`.
- Converted the `order_date` from string to proper datetime format for time-based analysis.
- Removed redundant columns: `list_price`, `cost_price`, and `discount_percent`.

### 🔹 SQL Integration
- Established a connection to Microsoft SQL Server using SQLAlchemy.
- Loaded the cleaned dataset into SQL Server (`df_orders` table) using the `append` mode, ensuring existing data isn't overwritten.

---

##  Technologies Used

- **Python**: Data processing, cleaning, and integration
- **Pandas**: Data manipulation
- **SQLAlchemy**: Python-SQL Server connection
- **Microsoft SQL Server**: Data warehousing and querying
- **Kaggle API**: Dataset download automation
- **Jupyter Notebook**: Development and experimentation environment

---

##  Files in This Repository

| File Name               | Description |
|------------------------|-------------|
| `orders.csv`           | Raw dataset from Kaggle |
| `orders data analysis.py` | Python script for the complete data pipeline |
| `sql_code.sql`         | SQL file with table schema and queries (if any) |
| `README.md`            | This documentation |

---

## Outcomes

- Created a clean, reliable, and analytics-ready dataset.
- Successfully pushed the data into SQL Server for advanced querying.
- Demonstrated integration of Python automation with enterprise-grade database systems.
- Enhanced data reliability by programmatically handling null values and standardizing formats.

---

## Author

**Thikkavarapu Sanhith**  
Aspiring Data Analyst | Skilled in Python, SQL, Data Cleaning, and BI Tools  
📫 [Connect on LinkedIn](https://www.linkedin.com/in/sanhith30/) *

---


This project demonstrates my hands-on capability in:
- Automating data pipelines
- Connecting Python scripts with SQL-based storage solutions
- Performing essential EDA and feature engineering for business-focused datasets

I’d love to discuss how I can bring these skills to your team. Let’s connect!

---
