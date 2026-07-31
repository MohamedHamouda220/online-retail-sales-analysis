# 📊 Online Retail Sales Analysis using Excel & Power BI

Transforming raw retail transactions into interactive business insights through data cleaning, modeling, DAX, and dashboard design.

<p align="center">
  <img src="online-retail-sales-project/dashboard.png" width="100%">
</p>

---

# 📑 Table of Contents

- [Project Overview](#-project-overview)
- [Dataset](#-dataset)
- [Tools & Technologies](#-tools--technologies)
- [Project Workflow](#-project-workflow)
- [Data Cleaning](#-data-cleaning)
- [Data Model](#-data-model)
- [DAX Measures](#-dax-measures)
- [Dashboard Features](#-dashboard-features)
- [Business Questions](#-business-questions)
- [Key Insights](#-key-insights)
- [Business Recommendations](#-business-recommendations)
- [Project Structure](#-project-structure)
- [Skills Demonstrated](#-skills-demonstrated)
- [Future Improvements](#-future-improvements)
- [Author](#-author)

---

# 📌 Project Overview

This project presents a complete end-to-end sales analysis of the **Online Retail Dataset** using **Microsoft Excel** and **Microsoft Power BI**.

The project follows the complete analytics workflow:

- Data Auditing
- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Business Analysis
- Data Modeling
- DAX Calculations
- Interactive Dashboard Design
- Business Insights & Recommendations

The objective is to transform raw transactional data into meaningful insights that support business decision-making.

---

# 📂 Dataset

**Dataset:** Online Retail Dataset

**Source**

https://archive.ics.uci.edu/dataset/352/online+retail

### Dataset Information

- **Rows:** 541,910
- **Columns:** 8

| Column |
|---------|
| InvoiceNo |
| StockCode |
| Description |
| Quantity |
| InvoiceDate |
| UnitPrice |
| CustomerID |
| Country |

---

# 🛠 Tools & Technologies

- Microsoft Excel
- Microsoft Power BI
- Power Query
- DAX
- Pivot Tables
- Data Modeling

---

# 🔄 Project Workflow

```text
Raw Dataset
      │
      ▼
Data Auditing
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Business Questions
      │
      ▼
Power BI Data Model
      │
      ▼
DAX Measures
      │
      ▼
Interactive Dashboard
      │
      ▼
Business Insights
      │
      ▼
Recommendations
```

---

# 🧹 Data Cleaning

The dataset was thoroughly examined before visualization.

### Data Cleaning Steps

- Checked missing values
- Investigated duplicate records
- Validated data types
- Investigated cancelled invoices
- Investigated returned transactions
- Reviewed zero Unit Price records
- Removed unnecessary inconsistencies
- Created additional calculated columns

### Created Columns

- Total Sales
- Year
- Month
- Day
- Day Name
- Hour
- Quarter

### Cleaning Decisions

- Missing Customer IDs were retained because they may represent anonymous customers.
- Returned transactions were preserved for return analysis.
- Zero-priced records were investigated instead of being removed.
- Duplicate records were identified during the auditing phase.

<p align="center">
  <img src="online-retail-sales-project/cleaned-data.png" width="100%">
</p>

---

# ⭐ Data Model

A **Star Schema** was implemented in Power BI to improve performance and support time intelligence calculations.

### Fact Table

- Cleaned Online Retail

### Dimension Table

- DimDate

<p align="center">
  <img src="online-retail-sales-project/data-model.png" width="100%">
</p>

---

# 🧮 DAX Measures

The dashboard includes several business measures:

- Revenue
- Orders
- Customers
- Products Sold
- Average Order Value
- Average Basket Size
- Return Amount
- Return %
- Revenue MTD
- Revenue YTD
- Previous Month Revenue
- Growth %

---

# 📊 Dashboard Features

The Power BI dashboard includes:

- KPI Cards
- Monthly Revenue Trend
- Sales by Country Map
- Top Countries Analysis
- Top Returned Products
- Interactive Slicers
- Custom Tooltips
- Responsive Layout

<p align="center">
  <img src="online-retail-sales-project/dashboard.png" width="100%">
</p>

---

# 📈 Business Questions

This project answers important business questions such as:

- What is the total revenue?
- How many orders were completed?
- Which month generated the highest revenue?
- Which countries generate the highest revenue?
- Which products contribute the most revenue?
- Which products have the highest returns?
- What is the overall return percentage?

---

# 📈 Excel Analysis

Before building the Power BI dashboard, exploratory analysis was performed in Excel using Pivot Tables.

<p align="center">
  <img src="online-retail-sales-project/revenue-by-month-pivot.png" width="100%">
</p>

---

# 💡 Key Insights

- The United Kingdom generated the highest revenue.
- November recorded the highest monthly revenue.
- Revenue is concentrated in a small number of countries.
- Several products experience significantly higher return volumes than others.
- Sales show clear seasonal patterns throughout the year.

<p align="center">
  <img src="online-retail-sales-project/insights-recommendations.png" width="100%">
</p>

---

# ✅ Business Recommendations

- Maintain sufficient inventory for top-selling products.
- Increase marketing campaigns before peak sales months.
- Investigate products with high return rates.
- Strengthen customer retention strategies.
- Expand business opportunities in high-performing countries.

---

# 📁 Project Structure

```text
online-retail-sales-analysis

│
├── Excel
│   ├── Cleaning Workbook.xlsx
│   └── Analysis Workbook.xlsx
│
├── Power BI
│   └── Online Retail Dashboard.pbix
│
├── online-retail-sales-project
│   ├── dashboard.png
│   ├── cleaned-data.png
│   ├── data-model.png
│   ├── revenue-by-month-pivot.png
│   └── insights-recommendations.png
│
├── README.md
└── LICENSE
```

---

# 🚀 Skills Demonstrated

- Data Cleaning
- Data Auditing
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Business Analysis
- Data Modeling
- Power Query
- DAX
- Dashboard Design
- Data Visualization
- KPI Development
- Storytelling with Data

---

# 🔮 Future Improvements

- SQL version of the project
- Customer Segmentation (RFM Analysis)
- Sales Forecasting using Python
- Predictive Analytics
- Power BI Service Deployment

---

# 👨‍💻 Author

**Mohamed Hamouda**

Aspiring Data Analyst

- GitHub: https://github.com/MohamedHamouda220
- LinkedIn: https://www.linkedin.com/in/mohammed-hamouda-394b6b416/

---

⭐ If you found this project useful, consider giving it a star.
