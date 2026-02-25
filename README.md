# 🧠 Customer Behavior Analytics | End-to-End Data Analyst Project

## 📌 Project Overview

This project simulates a real-world retail analytics engagement where transactional customer data is transformed into actionable business insights.

Using Python, SQL, and Power BI, I designed and implemented a complete analytics pipeline to analyze purchasing behavior, customer loyalty patterns, discount sensitivity, and revenue drivers.

The objective was to demonstrate how businesses can leverage customer data to improve retention, optimize marketing strategy, and increase revenue.

---

## 🎯 Business Problem

A retail company wants to better understand:

- What drives customer spending?
- Do discounts increase long-term value or only short-term sales?
- Are subscription members more profitable?
- Which customer segments contribute the most revenue?
- How do demographics influence purchasing behavior?

This project answers these questions using structured data analysis.

---

## 🛠️ Tools & Technologies

- **Python (Pandas, NumPy)** – Data cleaning & feature engineering  
- **PostgreSQL** – Business-driven SQL analysis  
- **Power BI** – Interactive dashboard & visualization  
- **Jupyter Notebook** – Workflow documentation  

---

## 📊 Dataset Summary

- 3,900 customer transactions  
- 18 attributes  
- Demographics, purchase behavior, product details, discounts, reviews, shipping, subscription status  
- Missing values handled using category-level median imputation  

---

## 🔎 Project Workflow

### 1️⃣ Data Preparation & Feature Engineering (Python)

- Cleaned and standardized dataset  
- Handled missing review ratings using median per product category  
- Created derived features:
  - Age groups  
  - Purchase frequency  
  - Customer loyalty segments  
- Loaded cleaned data into PostgreSQL for analysis  

---

### 2️⃣ Business Analysis (SQL)

Performed analytical queries to answer key stakeholder questions:

- Revenue contribution by gender  
- High-spending discount users  
- Shipping type vs average purchase value  
- Subscription vs non-subscription revenue comparison  
- Top-rated and best-selling products  
- Revenue contribution by age group  
- Repeat buyers vs subscription behavior  

---

### 3️⃣ Customer Segmentation

Customers were classified into:

- New  
- Returning  
- Loyal  

Segmentation was based on purchase history to evaluate loyalty distribution and revenue impact.

---

### 4️⃣ Power BI Executive Dashboard

Built an interactive dashboard presenting:

- Revenue by category  
- Sales by age group  
- Subscription distribution  
- Average purchase amount  
- Product rating insights  

The dashboard enables quick identification of revenue drivers and customer trends.

---

## 💡 Key Insights

- Loyal customers account for the majority of transactions.  
- Some products show high discount dependency, indicating potential margin risk.  
- Subscription status does not significantly increase average spending.  
- Express shipping customers show slightly higher average purchase value.  
- Young Adults generate the highest revenue contribution.

---

## 📈 Business Recommendations

- Optimize discount strategies to protect margins.  
- Strengthen loyalty program benefits.  
- Promote high-rated and best-selling products in campaigns.  
- Target high-revenue age segments with personalized marketing.

---

## 📂 Repository Structure

- `Customer_Shopping_Behavior_Analysis.ipynb` → Python data workflow  
- `customer_behavior_sql_queries.sql` → Business SQL queries  
- `customer_behavior_dashboard.pbix` → Power BI dashboard  
- `customer_shopping_behavior.csv` → Raw dataset  

---

## 🚀 What This Project Demonstrates

✔ End-to-end data analytics workflow  
✔ Business-oriented SQL analysis  
✔ Feature engineering & data cleaning  
✔ Interactive dashboard design  
✔ Translating data into strategic recommendations  
