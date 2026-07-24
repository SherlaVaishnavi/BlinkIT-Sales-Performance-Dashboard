# BlinkIT Sales Performance Dashboard

## Project Overview

The BlinkIT Sales Performance Dashboard is an interactive Business Intelligence project developed using Power BI. The dashboard analyzes sales data to provide valuable insights into product performance, outlet performance, customer ratings, and overall sales trends.

The objective of this project is to transform raw sales data into meaningful visualizations that support business decision-making.

---

## Business Problem

BlinkIT operates across multiple outlets and sells a wide range of grocery products. Analyzing large volumes of sales data manually is challenging. This dashboard helps identify key business trends, monitor performance, and support data-driven decisions.

---

## Dataset

The project uses multiple datasets organized using a Star Schema.

### Fact Table
- Fact_Sales

### Dimension Tables
- Dim_Items
- Dim_Outlet
- Dim_Cities
- Dim_FatContent
- Dim_Location

---

## Tools & Technologies

- Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling (Star Schema)

---

## Project Workflow

### Data Loading
Imported multiple datasets into Power BI Desktop.

### Data Cleaning
- Removed duplicate records
- Handled missing values
- Corrected data types
- Standardized data for analysis

### Data Modeling
Created relationships between the Fact table and Dimension tables using a Star Schema.

### DAX Measures
Created measures to calculate:
- Total Sales
- Average Sales
- Total Items Sold
- Average Rating
- Number of Outlets

### Dashboard Development
Built interactive dashboards using:
- KPI Cards
- Bar Charts
- Donut Charts
- Line Charts
- Matrix Tables
- Slicers

---

## Dashboard Insights

- Identified the highest-selling product categories.
- Compared sales across outlet types and outlet sizes.
- Analyzed sales distribution by fat content.
- Evaluated outlet performance across different locations.
- Monitored customer ratings and overall sales performance.

---

## Repository Structure

```
BlinkIT-Sales-Performance-Dashboard
│
├── BlinkIT_Dashboard.pbix
├── BlinkIT_Dashboard.pdf
├── README.md
├── Dataset/
```

---

## Learning Outcomes

Through this project, I gained hands-on experience in:

- Data Cleaning using Power Query
- Data Modeling
- DAX Calculations
- Dashboard Design
- Business Intelligence
- Data Visualization

---

## Author

**Sherla Vaishnavi**

Aspiring Data Analyst | Power BI | SQL | Python
