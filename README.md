# walmart-sql-python-project
An end-to-end data analysis project using SQL and Python on Walmart sales data
# Walmart Data Analysis: End-to-End SQL + Python Project 🛒📊

[Walmart Sales Analysis]

## 🚀 Project Overview

This is an end-to-end data analysis project focused on deriving meaningful business insights from Walmart sales data. It combines the power of **Python**, **SQL**, and structured data processing to explore, clean, transform, and analyze real-world data.

> 📌 Ideal for aspiring **data analysts** and **data scientists** to showcase SQL, Python, and business problem-solving skills.

---

## 📁 Project Structure

```plaintext
walmart-data-analysis/
├── data/                     # Raw and cleaned data
├── sql_queries/              # SQL scripts for business questions
├── notebooks/                # Jupyter notebooks for EDA and processing
├── README.md                 # Project documentation
├── requirements.txt          # Python dependencies
└── main.py                   # Core Python script for data pipeline
🛠️ Tools & Technologies
Languages: Python, SQL (MySQL & PostgreSQL)

Libraries: pandas, numpy, sqlalchemy, mysql-connector-python, psycopg2

IDE: VS Code

Data Source: Kaggle - Walmart 10K Sales Dataset

🔄 Project Workflow
1. Environment Setup
Created clean folder structure and VS Code workspace

Installed required Python libraries

2. Kaggle API Integration
Used kaggle.json to pull data via Kaggle API

3. Data Loading & Cleaning
Removed duplicates and missing values

Converted columns to proper data types (e.g., datetime, float)

Cleaned currency columns using .replace() and .astype()

4. Feature Engineering
Added total column = unit_price × quantity

5. Load to Databases
Loaded cleaned dataset into MySQL and PostgreSQL using SQLAlchemy

Verified with sample queries

6. SQL Business Analysis
Answered key business questions like:

Revenue trends by branch & category

Best-selling product categories

Sales performance by city, time, and payment method

Peak hours and customer behavior

Profitability analysis

7. Documentation & Publishing
All code and queries documented in Markdown and notebooks

Uploaded project to GitHub with README.md and query scripts

📊 Insights & Findings
🏬 Branch A has the highest total revenue, mainly in Food & Beverages

💳 Ewallet is the most preferred payment method

⏰ Most purchases happen in the evening hours

📈 Electronics category gives the highest profit margins

📌 Requirements
Python 3.8+

SQL Databases: MySQL & PostgreSQL

Required libraries:pip install pandas numpy sqlalchemy mysql-connector-python psycopg2


---

Let me know if you'd like:
- A `requirements.txt` file
- Help with GitHub setup steps
- A LinkedIn post to showcase your project

I'm ready!
