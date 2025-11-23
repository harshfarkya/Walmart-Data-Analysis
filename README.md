# Walmart Sales Analysis – Data Analytics Project

## 📌 Project Overview
This project analyzes Walmart's sales data to uncover insights related to customer behavior, category performance, revenue trends, and operational patterns across branches.  
The project uses **Python for data cleaning** and **MySQL for analytical queries**.

---

## 🛠 Tech Stack
- Python (Pandas)
- MySQL
- Jupyter Notebook

---

## 📂 Project Workflow

### 1. Data Exploration
- Used `.info()`, `.describe()`, `.head()` to examine structure
- Checked column types, missing values, and overall dataset health

### 2. Data Cleaning (Python)
- Removed duplicates  
- Handled missing values  
- Corrected data types  
- Cleaned currency formats  
- Validated final dataset  

### 3. Feature Engineering
- Added `Total Amount = unit_price * quantity`
- Prepared data for analysis and aggregation

### 4. Data Loading to MySQL
- Created tables using SQLAlchemy  
- Inserted cleaned data  
- Verified row counts and schema

### 5. SQL-Based Business Analysis
Ran 9 key analysis queries:
1. Payment method usage  
2. Highest-rated categories  
3. Busiest day per branch  
4. Quantity sold by payment method  
5. Category ratings per city  
6. Total profit by category  
7. Preferred payment method per branch  
8. Shift-wise sales  
9. Revenue decline YoY  

---

## 📊 Key Insights
- Digital payments dominate (E-wallet + Credit Card)
- Afternoon is the busiest shift; morning is slowest
- Fashion & Home categories drive highest profits
- Food, Sports, and Health categories highly rated across branches
- Several branches show significant YoY revenue decline

---

## 🎯 Business Recommendations
- Improve digital payment support & offer incentives  
- Allocate more staff during afternoon peak hours  
- Promote top-performing categories  
- Investigate underperforming branches  
- Use city-level category performance for targeted marketing  

---

## 📎 Files in This Repository
- `data_cleaning.ipynb` – Python cleaning
- `walmart_analysis.sql` – All SQL queries   
- `README.md` – Project documentation  

---

## 👤 Author
**Harsh Farkya**  
Data Analyst | Python | SQL | Power BI  

---

## ⭐ If you found this useful, consider giving the repository a star!
