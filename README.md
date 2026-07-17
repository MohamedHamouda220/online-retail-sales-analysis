# 📊 Online Retail Sales Analysis using Microsoft Excel

## 📌 Project Overview

This project analyzes the **Online Retail** dataset using **Microsoft Excel**.  
The goal was to perform the complete data analysis workflow, starting from data auditing and cleaning, then preparing the data, calculating KPIs, answering business questions using Pivot Tables, and finally extracting actionable business insights and recommendations.

---

## 📂 Dataset

- **Dataset:** Online Retail Dataset
- **Rows:** 541,910
- **Columns:** 8

### Columns

- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

---

## 🛠️ Tools Used

- Microsoft Excel
- Pivot Tables
- Excel Functions
- Data Filtering & Sorting

---

## 🧹 Data Cleaning Process

During the data cleaning phase, the following checks were performed:

- Checked for missing values
- Identified duplicate records
- Investigated negative quantities
- Checked zero unit prices
- Verified data types
- Investigated cancelled orders
- Created calculated columns:
  - Total Sales
  - Year
  - Month
  - Day Name
  - Hour
  - Quarter

### Cleaning Decisions

- Missing `CustomerID` values were retained because they may represent anonymous customers.
- Negative quantities were kept because they represent returned orders.
- Orders with `UnitPrice = 0` were investigated instead of being removed.
- Duplicate rows were identified during the audit.

---

## 📈 KPIs

The following KPIs were calculated:

- Total Revenue
- Total Orders
- Total Customers
- Total Quantity Sold
- Average Order Value

---

## 📊 Business Questions

This project answers the following business questions:

1. What are the top 10 products by revenue?
2. What are the top 10 products by quantity sold?
3. Which month generated the highest revenue?
4. Which country generated the highest revenue?
5. Who are the top customers?
6. Which products are returned the most?

---

## 💡 Key Insights

- "DOTCOM POSTAGE" generated the highest revenue.
- "WORLD WAR 2 GLIDERS ASSTD DESIGNS" was the best-selling product by quantity.
- November generated the highest revenue.
- The United Kingdom generated the highest revenue.
- Customer **14646** generated the highest revenue.
- "Printing smudges/thrown away" was the most returned product.

---

## ✅ Recommendations

- Maintain sufficient inventory for best-selling products.
- Increase marketing efforts before November.
- Focus on retaining high-value customers through loyalty programs.
- Investigate products with high return rates.
- Continue strengthening the UK market while exploring opportunities in other countries.

---

## 📁 Repository Contents

- Online_Retail_Project.xlsx
- README.md

---

## 🚀 Future Improvements

- Rebuild the analysis using SQL.
- Create an interactive Power BI dashboard.
- Perform advanced customer segmentation.
- Build sales forecasting models using Python.

---

## 👨‍💻 Author

**Mohamed Hamouda**

Junior Data Analyst (Aspiring)

GitHub:
https://github.com/MohamedHamouda220
