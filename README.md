# 🏦 Bank Loan Portfolio Analysis Dashboard

This project is focused on building an interactive dashboard to help banks better understand their loan portfolio, assess risk, and make informed lending decisions.

## 🎯 Project Goals

- Analyze loan applications, funded amounts, and repayments
- Track borrower risk indicators like DTI and interest rates
- Identify trends over time (MTD, MoM)
- Segment data by region, employment, purpose, and more
- Present the findings through a dynamic, filterable Power BI dashboard

---

## 📊 Tools & Technologies

- **PostgreSQL** – For structured data storage and querying
- **SQL** – For extracting, aggregating, and transforming data
- **Power BI** – For building the interactive dashboard
- **Kaggle Dataset** – Bank loan dataset (38,575 rows, 24 columns)

---

## 🧾 Dataset Overview

- **Source:** Kaggle (Public Loan Data)
- **Rows:** 38,575  
- **Fields Include:**
  - Loan ID, Issue Date, Amount, Total Payment
  - Interest Rate (`int_rate`), DTI (`dti`), Purpose
  - Loan Status, Home Ownership, Employment Length
  - Address State, Loan Term

---

## 🧠 SQL Modules Developed

✅ **Main KPIs**
- Total Applications, Funded Amount, Received Amount
- Average Interest Rate, Average DTI
- MTD (Month-to-Date) and MoM (Month-over-Month) values

✅ **Loan Quality Analysis**
- Categorization into **Good Loans** and **Bad Loans**
- Aggregated applications and payments for each category

✅ **Loan Status Grid**
- Group-wise breakdown (e.g., Fully Paid, Charged-Off) of all major metrics

✅ **Charts Data Preparation**
- Trends over time (monthly)
- Breakdown by:
  - State (Regional Analysis)
  - Loan Term
  - Employment Length
  - Loan Purpose
  - Home Ownership

All queries were documented and verified before importing into Power BI.

---

## 📈 Power BI Dashboard Features

- **Monthly Trends:** Loan activity over time using Line Charts
- **State-Wise Analysis:** Filled Maps showing region-based performance
- **Loan Term Breakdown:** Donut Charts showing 36 vs. 60-month loans
- **Employment & Purpose Analysis:** Bar Charts for borrower insights
- **Home Ownership:** Treemap showing loan volumes by ownership type
- **Interactive Slicers & Filters:** Explore by grade, state, loan type, etc.

---


