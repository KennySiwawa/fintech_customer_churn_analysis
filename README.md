# 📊 Customer Churn Analysis for a FinTech Bank

## 🚀 Project Overview

Customer retention is a critical challenge in the FinTech industry. This project analyzes bank customer data to identify churn patterns, understand key drivers of attrition, and provide data-driven recommendations to improve retention.

This project focuses on end-to-end analytics, emphasizing business insights, SQL-based analysis, and dashboard-driven decision-making.

---

## 🧠 Business Problem

The bank is experiencing customer churn, leading to:

- Loss of revenue
- Increased customer acquisition costs
- Reduced customer lifetime value (CLV)

## 🎯 Objectives

- Identify who is churning
- Understand why customers churn
- Quantify business impact (revenue at risk)
- Recommend strategies to reduce churn

---

## 📁 Project Structure

```text
churn-analysis-fintech/
│
├── data/
│   └── churn.csv
├── notebooks/
│   └── eda_analysis.ipynb
├── sql/
│   └── churn_queries.sql
├── dashboard/
│   └── powerbi.pbix
├── reports/
│   └── insights_summary.md
└── README.md
```

---

## 📊 Dataset

- Source: Kaggle (Bank Customer Churn Dataset)
- Records: ~10,000 customers
- Features include:
  - Demographics: Age, Gender, Geography
  - Financial: Balance, Estimated Salary
  - Behavior: Number of Products, Activity Status
  - Lifecycle: Tenure
- Target: Exited (1 = churned, 0 = retained)

---

## 🛠️ Tools & Technologies

- Python (Pandas, Matplotlib) — Data analysis & visualization
- SQL (SQLite/PostgreSQL) — Data querying & segmentation
- Power BI — Dashboard & business reporting
- GitHub — Version control & project showcase

---

## 🔍 Analysis Approach

1. **Data Cleaning**
   - Checked for missing values and duplicates
   - Validated data types and ranges
2. **Exploratory Data Analysis (EDA)**
   - Customer distribution analysis
   - Churn rate calculation
   - Feature-level exploration
3. **Customer Segmentation Analysis**

   Churn was analyzed across key dimensions:

   - **Demographics:** Age groups, Gender, Geography
   - **Financial behavior:** Account balance bands, Estimated salary
   - **Engagement:** Active vs inactive customers, number of products
   - **Lifecycle:** Tenure groups (early vs long-term customers)

4. **SQL Analysis**

   Business questions answered using SQL:

   - Churn rate by country
   - High-value customers who churned
   - Impact of customer activity on churn

5. **Dashboard (Power BI)**

   Interactive dashboard includes:

   - KPI cards (Churn %, Retention %, Revenue at Risk)
   - Churn by Age, Geography, Activity
   - Customer segmentation filters
