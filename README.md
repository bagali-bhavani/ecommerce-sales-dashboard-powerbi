# 📊 E-Commerce Sales Performance Dashboard | Excel & Power BI

![Dashboard Overview](images/dashboard-overview.png)

## 📌 Overview

The **E-Commerce Sales Performance Dashboard** is an interactive Business Intelligence project built using **Microsoft Excel** and **Power BI**. It transforms raw e-commerce sales data into meaningful insights through **data modeling, Power Query, DAX calculations, Time Intelligence, and interactive visualizations**.

The dashboard helps users track key business metrics, compare current performance with the previous year, evaluate product and regional performance, and analyze sales trends using dynamic filters.

---

## 🎯 Project Objective

The objective of this project is to build an interactive sales dashboard that enables business users to monitor performance, identify trends, and make better data-driven decisions.

This dashboard focuses on:
- Measuring Year-to-Date sales performance
- Comparing current performance with previous-year results
- Identifying top-performing and low-performing products
- Analyzing sales across regions, categories, and shipping methods
- Enabling dynamic filtering by customer segment

---

## ❗ Business Problem

Raw transactional data alone does not provide meaningful business insights. Decision-makers need a centralized and interactive reporting solution to monitor sales, profit, product performance, customer behavior, and geographical trends efficiently.

This dashboard addresses that need by converting raw e-commerce data into an easy-to-understand and interactive analytics solution.

---

## ✨ Key Features

- Interactive Power BI dashboard
- Star schema data model
- Calendar table for Time Intelligence
- Year-to-Date (YTD) analysis
- Previous Year-to-Date (PYTD) comparison
- Year-over-Year (YoY) analysis
- Dynamic KPI cards
- Conditional formatting
- Trend indicators
- Customer segment slicer
- Geographic sales analysis
- Top and bottom product analysis

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Microsoft Excel / CSV | Source data |
| Power BI Desktop | Dashboard development |
| Power Query | Data cleaning and transformation |
| DAX | KPI and Time Intelligence calculations |
| Data Modeling | Building relationships using star schema |

---

## 📂 Dataset

The project uses the following datasets:

| Dataset | Description |
|---------|-------------|
| `ecommerce-sales-data.csv` | Transactional e-commerce sales data |
| `us-state-coordinates.csv` | U.S. state latitude and longitude lookup table for map visualization |

---

## 🏗️ Data Model

The dashboard follows a **Star Schema** consisting of one fact table and two dimension tables.

### Fact Table
- `ecommerce_sales_data`

### Dimension Tables
- `Calendar`
- `us_state_coordinates`

The **Calendar** table supports Time Intelligence calculations, while the **us_state_coordinates** table enables state-level geographic analysis.

---

## 📊 Dashboard Highlights

The dashboard includes the following business views:

- YTD Sales
- YTD Profit
- YTD Quantity
- YTD Profit Margin
- Sales by Category
- Top 5 Products by Sales
- Bottom 5 Products by Sales
- Sales by Region
- Sales by Shipping Type
- Sales by State (Map)
- Customer Segment Filter

---

## 📈 DAX & Time Intelligence

Implemented DAX measures include:

- YTD Sales
- YTD Profit
- YTD Quantity
- PYTD Sales
- PYTD Profit
- PYTD Quantity
- YoY Sales
- YoY Profit
- YoY Quantity
- Profit Margin
- Dynamic KPI indicators
- Trend analysis
- Conditional formatting logic
- Dynamic icons

---

## 🖼️ Dashboard Preview

### Dashboard Overview

Default dashboard view showing overall business performance, including key KPIs, category-wise sales, regional analysis, shipping insights, and top/bottom product performance.

![Dashboard Overview](images/dashboard-overview.png)

---

### Interactive Filtering – Consumer Segment

Dashboard filtered for the **Consumer** customer segment to demonstrate slicer interaction and dynamic KPI updates across all visuals.

![Consumer Segment](images/dashboard-consumer-filter.png)

---

### Interactive Filtering – Corporate Segment

Dashboard filtered for the **Corporate** customer segment, showing how KPIs and charts update dynamically based on user selection.

![Corporate Segment](images/dashboard-corporate-filter.png)

---

### Data Model

Star Schema data model consisting of one fact table and two dimension tables, designed to support efficient reporting and Time Intelligence calculations.

![Data Model](images/data-model.png)

---

## 💡 Business Insights

This dashboard enables users to:

- Monitor overall sales performance using Year-to-Date metrics
- Compare current business performance with the previous year
- Identify high-performing and underperforming products
- Analyze category contribution to total sales
- Evaluate regional sales distribution
- Understand shipping method preferences
- Visualize sales performance across U.S. states
- Interact dynamically using customer segment filters

---

## 📋 Requirements

To use this project, you will need:

- **Microsoft Power BI Desktop**
- **Microsoft Excel** (optional, for viewing source data)

---

## 🚀 How to Use

1. Clone or download this repository.
2. Open **E-Commerce Sales Performance Dashboard.pbix** in **Power BI Desktop**.
3. Refresh the data if prompted.
4. Use the **Customer Segment** slicer to interact with the dashboard.

---

## 📁 Repository Structure

```bash
ecommerce-sales-dashboard-powerbi/
│
├── README.md
├── .gitignore
├── E-Commerce Sales Performance Dashboard.pbix
├── ecommerce-sales-data.csv
├── us-state-coordinates.csv
│
└── images/
    ├── dashboard-overview.png
    ├── dashboard-consumer-filter.png
    ├── dashboard-corporate-filter.png
    └── data-model.png
```

---

## 🔮 Future Improvements

- Drill-through report pages
- Tooltip pages for enhanced interactivity
- Customer-level performance analysis
- Forecasting and trend prediction
- Additional business KPIs

---

## 👤 Author

**Bhavani Bagali**

Aspiring **Data Analyst** passionate about transforming data into meaningful business insights using **Excel, SQL, Python, and Power BI**.

---

⭐ If you found this project interesting, consider giving the repository a star.
