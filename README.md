# 📊 Amazon Sales Analytics Dashboard

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Data%20Analysis-blue?style=for-the-badge)
![Power Query](https://img.shields.io/badge/Power%20Query-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

## 📌 Project Overview
This project is an interactive Sales Analytics Dashboard built in Power BI to analyze sales performance, customer churn, and inventory for an Amazon-style e-commerce dataset. It combines multiple related data tables (sales, stock, SKU, and city data) into a single data model, providing a 360° view of business performance to support data-driven decisions.

---

## 📸 Dashboard Preview

### Churn Analysis
![Churn Analysis](images/churn_analysis.png)

### Stock Analysis
![Stock Analysis](images/stock_analysis.png)

### Regional Sales Analysis
![Regional Sales Analysis](images/regional_sales_analysis.png)

### State-wise Sales Map
![State Sales Map](images/state_sales_map.png)

---

## 🎯 Project Objectives
- Monitor overall sales performance and key business KPIs
- Analyze customer churn and retention patterns
- Track inventory and stock levels across categories, sizes, and colors
- Explore regional and geographic sales distribution
- Support data-driven decision-making with interactive filtering

---

## 📄 Dashboard Pages

### Churn Analysis
**KPIs**
- Total Customers
- Repeat Customers
- Churned Customers
- New Customers

**Visualizations**
- New Customers by Category
- Churned Customers by Category
- Top 15 States by New Customer Sales
- Top 15 States by Churned Customer Sales
- Sales by City (New vs. Churned Customers)

---

### Stock Analysis
**KPIs**
- Total Sales
- Total Stock Count
- Stock Count (Variant)
- Latest Stock Count

**Visualizations**
- Stock Count by Color
- Latest Stock by Category
- Latest Stock by Size
- Latest Stock by Category (breakdown)

---

### Regional Sales Analysis
**KPIs**
- Total Customers
- Total Products
- Sales
- Sales (Same Period Last Year)
- Sales (Last Month)
- Last Month Growth %
- Year-over-Year Growth %

**Visualizations**
- Sales by State, City, and Category
- Sales by Category
- Top 10 Cities by Sales
- Monthly Sales Trend vs. Prior Year with YoY Growth %

---

### State-wise Sales Map
**Visualizations**
- Geographic distribution of sales across U.S. states (bubble map)
- Filterable by Year, Month, State, and Category

---

## 🛠 Tools & Technologies
- Power BI
- Power Query (data transformation and cleaning)
- Data Modeling (relationships across Sales, Stock, SKU, and City tables)
- DAX (calculated measures & KPIs)
- Data Visualization

---

## 🔗 Data Model
The project connects and relates four core tables into a single data model:
- **Sales** — transactional sales data
- **Stock** — inventory and stock levels
- **SKU** — product/category details
- **City** — geographic reference data

Relationships between these tables enable cross-filtering across all four dashboard pages.

---

## 📂 Dataset
Amazon-style e-commerce sales dataset (aggregated, no personally identifiable information).

---

## 📁 Repository Structure
```text
amazon-sales-analysis-powerbi
│
├── amazon_sales_analysis.pbix
├── README.md
└── screenshots
    ├── churn_analysis.png
    ├── stock_analysis.png
    ├── regional_sales_analysis.png
    └── state_sales_map.png
```

---

## ⭐ Key Features
- Interactive dashboards with dynamic slicers (Year, Month, Category, Size, Color, State)
- Multi-table data model with defined relationships
- Customer churn and retention tracking
- Inventory and stock-level monitoring
- Regional and geographic sales analysis
- Month-over-month and year-over-year growth comparisons
- Clean and user-friendly dashboard design

---

## 🤝 Connect
If you have any feedback or suggestions, feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/aydamirova).

---
**Author:** Sevil Aydamirova
Data Analyst | Excel | Power BI | SQL | Python |
