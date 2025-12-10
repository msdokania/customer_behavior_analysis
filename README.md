# Data Analytics Project – End-to-End Pipeline (Python, SQL, Power BI)

This project demonstrates a complete, industry standard, end-to-end data analytics workflow—from loading and exploring a dataset in Python, to cleaning and transforming the data, running SQL queries using PostgreSQL, and building an interactive Power BI dashboard. It also includes a final business insights report and presentation.

---

## 🔍 1. Project Overview

The goal of this project is to simulate a corporate-grade end-to-end data analytics workflow, demonstrating the ability to translate raw data into strategic business intelligence through:

- Exploratory Data Analysis (EDA) in Python  
- Data cleaning and preprocessing  
- Data Analysis (SQL) to simulate business transactions, and run queries to extract insights on customer segments, loyalty, and purchase drivers. 
- Data visualization and storytelling in Power BI to highlight key patterns and trends
- Final business recommendations presented through a detailed report and slide deck  

This project simulates a practical analytics workflow used by data analysts and data engineers.

---

## 📁 2. Dataset

- **Source:** Sample dataset provided internally
- **Format:** CSV

---

## 🛠️ 3. Tools & Technologies

| Category         | Tools |
|------------------|-------|
| Programming      | Python (Pandas, NumPy, Matplotlib, Seaborn) |
| Database         | PostgreSQL + SQL |
| Visualization    | Power BI |
| Documentation    | Gamma App |
| Environment      | Jupyter Notebook |

---

## 🚀 4. Project Steps

### **Step 1 — Load & Explore Data (Python)**
- Loaded dataset using Pandas  
- Checked datatypes, missing values, duplicates  
- Performed descriptive statistics  
- Visualized distributions, correlations, and outliers  

### **Step 2 — Data Cleaning & Preprocessing**
- Handled missing values  
- Standardized and formatted columns  
- Removed inconsistencies and duplicates  
- Created engineered features for analysis  

### **Step 3 — SQL Analysis using PostgreSQL**
- Created database and imported cleaned dataset  
- Wrote SQL queries for:  
  - Aggregations  
  - Segmentation  
  - Time-series performance  
  - KPI analysis  
- Validated results against Python  

### **Step 4 — Power BI Dashboard**
- Connected Power BI to PostgreSQL  
- Designed analytics-ready data model  
- Built an interactive dashboard with:  
  - KPIs  
  - Trend charts  
  - Category breakdowns  
  - Filters and slicers  

### **Step 5 — Business Insights Report **
- Summarized findings  
- Highlighted key KPIs and trends  
- Explained data-driven recommendations  
- Created a visual slide deck  

---

## 📊 5. Dashboard & Results

The Power BI dashboard highlights:

- Top-performing segments  
- Sales trends  
- User or customer behavior patterns  
- Revenue drivers  
- Areas for business optimization  

---

## ▶️ 6. How to Run Locally

### **Prerequisites**
- Python 3.9+  
- PostgreSQL installed  
- Power BI Desktop (or Power BI Web + Gateway)  
- Jupyter Notebook  

## 🛠️ How to Use This Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/msdokania/customer_behavior_analysis.git
   ```
2. **Open Customer_Shopping_Behavior_Analysis.ipynb notebook**

    This file contains:

      - Data Import

      - Data exploration

      - Data cleaning

      - Connection to SQL Database
  
3. **Load the data from Python notebook into MySQL/PostgreSQL/MS SQL Server**

      - Create a database in SQL

      - Run Python code to load data into SQL database
  
      - Open **customer_behavior_sql_queries.sql**
  
      - Answer Business Questions using SQL Queries 
      
4. **Connect the SQL Database to Power BI**

      - Open **customer_behavior_dashboard.pbix**
   
      - Create interactive dashboard in Power BI
  
6. **Create Project Report and Presentation**

      - Create project report
   
      - Build presentation deck using Gamma AI
