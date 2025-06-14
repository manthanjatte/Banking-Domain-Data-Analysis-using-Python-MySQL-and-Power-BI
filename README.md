# 🏦 Banking Domain Data Analysis using Python, MySQL & Power BI

## 📖 Project Overview
This project focuses on analyzing banking customer data to uncover financial patterns and operational insights using tools like **Python**, **MySQL**, and **Power BI**. It aims to optimize customer management, revenue forecasting, and identify key financial indicators such as credit card usage, savings account distribution, and fee structures.

---

## 🧠 Objectives

- Perform data cleaning and transformation using Python (Pandas)
- Import and manage structured data using MySQL
- Design meaningful KPIs and dashboards in Power BI
- Calculate total fees, credit card balances, and savings accounts
- Segment customers by risk, loyalty, income, and product usage

---

## 📌 Dataset Description

The dataset consists of **3,000 banking customers** and includes:

- 👤 **Customer Info**: Name, Age, Gender, Location  
- 💳 **Account Details**: Saving Accounts, Credit Card Balances, Deposits  
- 💰 **Financial Behavior**: Fee Structure, Estimated Income, Loans  
- 🏷️ **Labels**: Loyalty Classification, Occupation, Risk Weighting

---

## 🛠️ Technologies Used

| Technology        | Purpose                                 |
|-------------------|------------------------------------------|
| **Python**        | Data wrangling and feature engineering   |
| **Pandas**        | Tabular data manipulation                |
| **NumPy**         | Numeric operations                       |
| **MySQL**         | Database queries and integration         |
| **Power BI**      | Interactive dashboards and KPI visuals   |
| **Excel**         | Source data formatting                   |
| **DAX**           | Custom measures and calculated columns   |
| **Jupyter Notebook** | Exploratory analysis & transformation |

---

## 📈 Key Highlights

- Assigned numerical scores to categorical fee structures using `SWITCH()` in DAX
- Calculated:
  - Total Credit Card Balance
  - Total Saving Account Balance
  - Total Fee Revenue by Tier (High/Mid/Low)
- Created segment-wise dashboards showing:
  - Customer Distribution by Loyalty Tier & Risk Level
  - Financial product usage (Cards, Loans, Deposits)
  - Regional and occupational insights
- Used Power BI relationships to join multiple data views
- Integrated MySQL backend to pull transactional data live (if configured)

---

## 🔍 Insights Extracted

- Customers with **High Fee Structure** contribute to majority of revenue
- Users with **multiple credit cards and high deposits** are mostly in Platinum loyalty segment
- **Risk Weighting** and **Estimated Income** help predict upsell potential
- Most saving accounts are concentrated in middle-aged customer segments
- **Senior professionals and business owners** show higher deposit activity

---

## 🧩 Future Scope

- Automate report refresh via Power BI Gateway
- Connect live to MySQL or SQL Server database for real-time updates
- Integrate customer churn risk scoring using Python ML models
- Expand visual analytics using Power BI bookmarks and drill-throughs

---

## 👨‍💻 Author

**Manthan Jatte**  
Exploring **Python | SQL | Power BI | Data Analytics**  
