# 📊 European Pharmacy Analysis — End-to-End Power BI Business Intelligence Solution

## 📌 Project Overview

**European Pharmacy Analysis** is an end-to-end **Business Intelligence and Data Analytics project** developed using **Microsoft Power BI**.

The project focuses on transforming raw pharmacy transactional data collected from multiple European countries into meaningful business insights through interactive dashboards and analytical reports.

This solution enables business users, sales managers, and procurement teams to analyze:

- Revenue and profit performance
- Sales trends and growth patterns
- Regional business performance
- Product contribution and profitability
- Inventory efficiency

The dashboard converts complex business data into clear, actionable insights that support data-driven decision-making.

---

# 🎯 Business Objectives

The objective of this project is to build a centralized analytics solution that provides complete visibility into pharmacy sales, financial performance, and operational efficiency.

---

## 📈 Executive Performance Analysis

### Purpose:
Provides senior management with an overview of overall business performance.

### Key KPIs:

- 💰 Total Revenue
- 📊 Total Profit
- 📈 Profit Margin %
- 🔄 Year-over-Year (YoY) Growth
- 📦 Total Units Sold
- 🏪 Pharmacy Performance

### Business Impact:

Helps leadership teams monitor business growth, identify profitable areas, and make strategic decisions.

---

# 🌍 Regional Sales Analysis

### Purpose:
Analyzes sales performance across different European markets.

### Analysis Includes:

- Country-wise revenue comparison
- City-level sales performance
- Regional profit contribution
- High-performing and under-performing areas
- Seasonal sales trends

### Business Impact:

Enables regional teams to optimize sales strategies, improve market performance, and identify growth opportunities.

---

# 💊 Product & Inventory Analysis

### Purpose:
Supports procurement and product management teams with product-level insights.

### Key Analysis:

- Brand-wise revenue contribution
- Generic vs Non-Generic product analysis
- Product profitability comparison
- Product lifecycle monitoring
- Inventory performance tracking

### Business Impact:

Helps reduce inventory inefficiencies, improve purchasing decisions, and maximize product profitability.

---

# 📊 Dashboard Pages

## 1. Executive Overview Dashboard

### Objective:
Provides a complete business summary through interactive visualizations.

### Key Visuals:

- KPI Cards
- Revenue & Profit Trend Analysis
- Country Performance Map
- Monthly Sales Trend
- Growth Analysis
- Promotion Impact Analysis

### Business Questions Answered:

✔ What is the overall revenue and profit performance?

✔ Which countries generate the highest business value?

✔ Are sales improving over time?

✔ How effective are promotional activities?

---

# 2. Sales Analysis Dashboard

### Objective:
Provides detailed sales insights for sales and regional teams.

### Key Visuals:

- City-wise Sales Analysis
- Product Quantity Analysis
- Monthly Sales Trend
- Seasonal Demand Analysis
- Top Performing Locations

### Business Questions Answered:

✔ Which locations generate maximum sales?

✔ Which products have the highest demand?

✔ What are the seasonal sales patterns?

✔ Which regions require improvement?

---

# 3. Product & Pharmacy Insight Dashboard

### Objective:
Analyzes product performance and pharmacy-level efficiency.

### Key Visuals:

- Brand Performance Ranking
- Generic vs Non-Generic Analysis
- Pharmacy Revenue Ranking
- Product Profit Contribution
- Discontinued Product Analysis

### Business Questions Answered:

✔ Which products drive maximum profit?

✔ Which brands perform better?

✔ Which products need improvement?

✔ Which pharmacies contribute the most revenue?

---

# 🏗 Data Architecture

The project follows an industry-standard **Star Schema Data Model** for efficient reporting and analysis.

## Data Model Design

## ⭐ Fact Table

### Fact_Sales

Contains transactional sales information:

- Transaction ID
- Date
- Product ID
- Pharmacy ID
- Location ID
- Quantity Sold
- Revenue
- Profit

---

## Dimension Tables

### Dim_Product

Contains product-related information:

- Product Name
- Brand
- Category
- Generic Type

---

### Dim_Pharmacy

Contains pharmacy details:

- Pharmacy Name
- Location
- Store Information

---

### Dim_Location

Contains geographical information:

- Country
- City
- Region

---

### Dim_Date

Contains time intelligence fields:

- Date
- Month
- Quarter
- Year

---

# 🛠 Tools & Technologies Used

| Technology | Purpose |
|---|---|
| Microsoft Power BI | Dashboard Development & Data Visualization |
| Power Query | Data Cleaning & Transformation |
| DAX | Measures, KPIs & Business Calculations |
| Data Modeling | Star Schema Design |
| Excel / CSV | Data Source Management |

---

# 🧹 Data Cleaning & Transformation (Power Query)

Performed data preparation steps:

- Removed duplicate records
- Handled missing values
- Changed data types
- Created calculated columns
- Standardized product and location data
- Prepared clean tables for modeling

---

# 📐 DAX Measures Developed

Created business-focused calculations:

- Total Revenue
- Total Profit
- Profit Margin %
- Sales Growth %
- Average Sales
- Product Contribution %
- Year-over-Year Comparison

Example:

```DAX
Total Revenue =
SUM(Fact_Sales[Revenue])


Total Profit =
SUM(Fact_Sales[Profit])


Profit Margin % =
DIVIDE(
    [Total Profit],
    [Total Revenue]
)
```

---

# 🚀 Project Outcomes

This Power BI solution helps the pharmacy business to:

✅ Monitor overall financial performance  
✅ Identify profitable products and brands  
✅ Improve inventory planning  
✅ Understand regional demand  
✅ Track sales growth trends  
✅ Support strategic business decisions  

---

# 👩‍💻 Skills Demonstrated

- Business Intelligence Development
- Data Analysis
- Data Cleaning
- Power Query Transformation
- DAX Development
- Data Modeling
- Dashboard Design
- KPI Development
- Business Requirement Analysis

---

# 📌 Project Category

**Data Analytics | Business Intelligence | Power BI Dashboard | Data Visualization**
