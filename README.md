# 🏦 Banking Dashboard Project

## 📌 Overview
This project demonstrates an **end-to-end data analysis pipeline** for banking data, combining **SQL, Python, and Power BI**.  
I connected a **MySQL database** to Python for **data extraction & exploratory data analysis (EDA)**, then developed an **interactive Power BI dashboard** to provide insights into customer demographics, loyalty tiers, and financial balances.  

The goal was to simulate a real-world workflow where raw data is transformed into business insights.

---

## 🛠️ Tools & Technologies
- **Database:** MySQL (`mysql-connector-python`)
- **Python:** Pandas, Matplotlib, Seaborn
- **Visualization:** Power BI (DAX, interactive visuals)
- **Version Control:** GitHub

---

## 🔍 Process

### 1. Data Connection & Cleaning
- Connected MySQL database to Python using `mysql-connector`.
- Cleaned missing values, removed duplicates, and ensured proper data types.
- Prepared dataset for visualization in Power BI.

### 2. Exploratory Data Analysis (EDA) in Python
- Analyzed customer demographics, loyalty classification, risk weighting, and financial balances.
- Created visualizations to identify trends, distributions, and outliers.
- Example insights:
  - Majority of clients fall into **Sapphire and Gold loyalty tiers**.
  - **Medium-to-high risk clients (3–4 weighting)** dominate the portfolio.
  - A few occupations account for the **largest share of loans & deposits**.

### 3. Power BI Dashboard Development
- Built an interactive summary dashboard featuring:
  - **KPI Cards:** Total Clients, Total Loans, Total Deposits, Loan-to-Deposit Ratio  
  - **Risk Distribution:** Clients categorized as Low (1–2), Medium (3), High (4–5)  
  - **Top 5 Occupations:** Ranked by total loans & deposits  
  - **Loyalty Classification Breakdown:** Ordered Jade → Diamond  
- Used DAX measures for loan-to-deposit ratio and custom categorization.

---
