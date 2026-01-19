# Customer_Shopping_behavior_Analysis

# 🛒 Customer Shopping Behavior Analysis  
**End-to-End Data Analytics Project using Python, SQL & Power BI**

---

## 📌 Project Overview
This project focuses on analyzing customer shopping behavior using retail transaction data to uncover insights that help businesses improve revenue, customer retention, and marketing effectiveness.

The analysis covers the complete data analytics lifecycle — from raw data preparation and exploration to business-driven SQL analysis and interactive dashboard creation.

This project is designed to simulate a real-world data analyst workflow.

---

## 🎯 Business Problem Statement
A retail company wants to understand how customers behave across different demographics, product categories, and purchasing conditions.

Key business questions include:
- Which customer segments generate the highest revenue?
- How do discounts and subscriptions affect spending?
- Does shipping type influence purchase value?
- What drives repeat purchases and customer loyalty?

The goal is to convert raw customer data into actionable business insights.

---

## 📊 Dataset Information
- **Total Records:** 3,900 customer transactions  
- **Total Columns:** 18  
- **Missing Values:** 37 values in the *Review Rating* column  

### Data Attributes Include:
- Customer Demographics: Age, Gender, Location  
- Purchase Details: Category, Item Purchased, Purchase Amount, Season  
- Behavioral Data: Discounts, Subscription Status, Shipping Type, Review Ratings  

---

## 🛠️ Tools & Technologies
- **Python:** Pandas, NumPy, Matplotlib, Seaborn  
- **SQL:** PostgreSQL  
- **Power BI:** Interactive dashboards & visual storytelling  
- **GitHub:** Version control and project documentation  

---

## 🔍 Project Workflow

### 1️⃣ Data Cleaning & Exploration (Python)
- Loaded raw dataset using Pandas
- Performed exploratory data analysis (EDA)
- Identified missing values and handled them using median imputation
- Standardized column names for consistency
- Created new features:
  - Age groups for demographic analysis
  - Purchase frequency metrics
- Validated data consistency before analysis

📄 File: `Customer_Shopping_Behavior_Analysis.ipynb`

---

### 2️⃣ Business Analysis (SQL)
The cleaned dataset was loaded into a PostgreSQL database to perform structured analysis.

Key SQL analyses include:
- Revenue comparison by gender
- Identification of high-spending customers using discounts
- Top-rated products based on customer reviews
- Impact of shipping type on purchase value
- Subscriber vs non-subscriber spending analysis
- Customer segmentation into New, Returning, and Loyal customers

📄 File: `customer_behavior_sql_queries.sql`

---

### 3️⃣ Data Visualization (Power BI)
An interactive Power BI dashboard was created to communicate insights to stakeholders.

Dashboard highlights:
- Revenue trends and customer segmentation
- Subscription and shipping impact on spending
- Top-performing and top-rated products
- Actionable KPIs for business decision-making

📄 File: `customer_behavior_dashboard.pbix`

---

## 💡 Key Insights
- Subscription customers contribute a significant share of total revenue
- Express shipping users have a higher average purchase value
- Female customers generate slightly higher total revenue than male customers
- Loyal customers drive long-term revenue growth

---

## 📈 Business Recommendations
- Promote subscription-based offers to increase customer lifetime value
- Strengthen loyalty programs to retain high-value customers
- Optimize discount strategies to balance revenue and profitability
- Focus marketing efforts on high-spending customer segments

---

