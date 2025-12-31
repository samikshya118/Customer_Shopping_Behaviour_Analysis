# 🛍️ Customer Shopping Trends Analysis  
### 📊 End-to-End Data Analytics Project

## 📖 Project Overview
This project demonstrates a **full-cycle data analytics workflow**, simulating a real-world corporate environment. The objective is to transform raw retail data into **actionable business insights** using an industry-standard analytics pipeline.

The project goes beyond basic visualization by integrating:
- **Python** for ETL (Extract, Transform, Load)
- **SQL** for data warehousing and analytical querying
- **Power BI** for interactive dashboards and stakeholder reporting

---

## 🔄 Project Architecture & Workflow

Raw CSV Data
↓
Python (Pandas) – Data Cleaning & Feature Engineering
↓
SQL Database – Storage & Analysis
↓
Power BI – Visualization & Dashboarding


### 🔧 Key Pipeline Stages
- **Data Engineering (Python)**
  - Ingested raw CSV data
  - Handled missing values using category-based median imputation
  - Engineered new features such as **Age Groups**
  - Standardized column formats for consistency

- **Database Management (SQL)**
  - Connected Python to SQL using SQLAlchemy
  - Loaded clean data into relational tables

- **Data Analysis (SQL)**
  - Wrote advanced SQL queries using:
    - Aggregate functions
    - Window functions
    - CASE-based conditional logic

- **Data Visualization (Power BI)**
  - Connected Power BI to a live SQL database
  - Built an interactive dashboard with KPIs and slicers

---

## 🛠️ Tech Stack & Skills Demonstrated

| Component | Technology | Skills Applied |
|--------|-----------|---------------|
| Programming | Python (Pandas, SQLAlchemy) | Data Cleaning, Null Imputation, Feature Engineering, DB Connectivity |
| Database | PostgreSQL / MySQL | DDL & DML, Window Functions, Aggregations, CASE Logic |
| Visualization | Microsoft Power BI | Data Modeling, DAX Measures, Interactive Slicers, KPIs |
| Presentation | Gamma AI | Automated Slide Decks, Data Storytelling |

---

## 📊 Key Business Insights & Analysis

This project answers several critical business questions:

- **Customer Segmentation**
  - Classified customers into **New**, **Returning**, and **Loyal** based on purchase frequency

- **Revenue Drivers**
  - Identified top-performing **Age Groups** and **Product Categories**

- **Shipping Analysis**
  - Analyzed how **Shipping Type** (Express vs. Standard) affects average transaction value

- **Seasonal Trends**
  - Mapped purchasing behavior across different seasons

---



## 🚀 How to Run This Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/customer-trends-analysis.git
cd customer-trends-analysis

2️⃣ Python Setup (ETL)

1 . Open Customer_Shopping_Behavior_Analysis.ipynb in Jupyter Notebook

2. Install required dependencies:

  pip install pandas sqlalchemy psycopg2-binary
  # OR (for MySQL users)
  pip install mysql-connector-python


3. Update database credentials in the notebook

4. Run all cells to clean data and load it into your SQL database


3️⃣ SQL Analysis

1. Open your SQL client (pgAdmin / MySQL Workbench)

2. Execute queries from:

  sql_queries/customer_behavior_queries.sql

4️⃣ Power BI Dashboard

1. Open customer_behavior_dashboard.pbix

2. Go to Transform Data → Data Source Settings

3. Update credentials to your local SQL instance

4. Click Refresh to load the data
