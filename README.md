# Contoso Sales Analysis Dashboard

## Project Overview

This project is an interactive **Power BI Sales Dashboard** built using the **Contoso Dataset** to analyze retail sales performance, profitability, customer orders, and regional business trends.

The dashboard helps stakeholders monitor KPIs, track Year-over-Year (YoY) growth, analyze product performance, and make data-driven business decisions using interactive visualizations and filters.

---

# Dashboard Preview

<img width="1250" height="729" alt="contoso_report_dashboard" src="https://github.com/user-attachments/assets/93a94c73-e9b1-4206-a7dd-34a756746286" />


---

# Business Problem

Retail businesses generate massive amounts of sales and operational data, but without proper analytics it becomes difficult to:

- Monitor profitability
- Track sales growth
- Analyze product performance
- Compare regional sales trends
- Understand yearly business growth
- Make strategic business decisions

This dashboard solves these problems by transforming raw Contoso retail data into meaningful business insights through interactive visualizations.

---

# Project Objectives

- Analyze sales, profits, and order performance
- Track Year-over-Year (YoY) profit growth
- Monitor historical running totals of profit
- Compare product brand performance
- Analyze regional and store-level business metrics
- Build interactive filters for dynamic reporting

---

# Tools & Technologies Used

- Power BI
- DAX (Data Analysis Expressions)
- Power Query
- Data Modeling
- Data Visualization

---

# Dataset Information

The project uses the **Contoso Retail Dataset** containing multiple related tables such as:

- Sales
- Product
- Product Category
- Product Subcategory
- Geography
- Store
- Date
- Channel

---



# Dashboard Visualizations & Insights

---

## 1. Net Profit By Month and Year

<img width="758" height="470" alt="image" src="https://github.com/user-attachments/assets/6b7aa669-ce64-48f8-a1b5-29ef60de29e0" />


### Insights

- Tracks monthly net profit trends across years.
- Includes YoY profit growth percentage comparison.
- Helps identify seasonal trends and low-performing months.
- Some months show negative YoY growth indicating reduced profitability.

### Business Impact

This visualization helps businesses monitor financial performance and identify months requiring strategic improvements.

---

## 2. Net Profit Running Total by Date Hierarchy

<img width="823" height="380" alt="image" src="https://github.com/user-attachments/assets/94253acd-a66a-4504-8bdb-830181884c6b" />


### Insights

- Displays cumulative profit growth over time.
- Shows steady business growth across quarters and years.
- Helps evaluate long-term company performance.

### Business Impact

Useful for tracking historical profitability and business expansion trends.

---

## 3. Year Over Year Net Profit by Product Brand

<img width="757" height="509" alt="image" src="https://github.com/user-attachments/assets/56bad1ea-9976-44d8-a19c-c101a079b2be" />


### Insights

- Highlights top-performing product brands.
- Identifies brands contributing most to profits.
- Helps compare yearly brand performance.

### Business Impact

Supports inventory planning, marketing strategy, and product optimization decisions.

---

## 4. Geography and Store Details Table

<img width="843" height="617" alt="image" src="https://github.com/user-attachments/assets/38276c67-cb56-46e4-bf9b-75e2add05cb6" />


### Insights

- Provides region-wise sales and profit analysis.
- Displays total sales, expenses, order count, and net profit.
- Enables comparison between countries, states, cities, and stores.

### Business Impact

Helps businesses identify profitable locations and optimize regional operations.

---

# Report Development Process

The dashboard was developed using the following workflow:

```text
Data Sources → Power Query → Data Model → Power BI Dashboard
```

---

# Power Query Transformations

## Essential Transformations Performed

- Removed unnecessary columns
- Renamed columns for readability
- Changed data types
- Removed null/empty columns
- Created custom columns
- Merged related tables




# Data Modeling

A relational data model was built between:

- Sales Table
- Product Master Table
- Geography Table
- Store Table
- Date Table
- Channel Table

Relationships were created to support accurate filtering and reporting.

---



# Key Learnings

Through this project, I learned:

- Data transformation using Power Query
- Building relational data models
- Writing DAX calculations and measures
- Creating KPI cards and advanced visualizations
- Implementing running totals and YoY analysis
- Designing interactive dashboards with slicers
- Business-focused data storytelling

---

# Conclusion

This Power BI dashboard successfully transforms raw Contoso retail data into actionable business insights. The dashboard enables users to monitor profitability, analyze regional sales performance, track yearly growth, and evaluate product brand performance through interactive reporting.

The project demonstrates practical skills in:

- Power BI Dashboard Development
- Data Modeling
- Power Query
- DAX Calculations
- Business Intelligence
- Data Visualization
- Retail Sales Analytics

