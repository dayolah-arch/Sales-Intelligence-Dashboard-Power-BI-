# Sales-Intelligence-Dashboard-Power-BI-
A dynamic Power BI Sales Dashboard showcasing revenue trends, regional performance, and product insights. Built with DAX measures and data modeling to help track KPIs, visualize trends, and support data-driven decision-making.
---

## 🚀 Key Features

- 📈 **Revenue Overview:** Total revenue, sales growth, and profit margin analysis  
- 🌎 **Regional Performance:** Interactive visuals showing sales distribution by region and sales representative  
- 🛍️ **Product Insights:** Top-performing products, category breakdown, and contribution margins  
- ⏱️ **Time-Based Analysis:** Monthly and quarterly trends with drill-through to individual product or region  
- 👥 **Customer Insights:** Sales by customer segment, repeat purchase rate, and retention metrics  
- 💡 **KPIs Tracked:** Total Revenue, Sales Growth %, Average Order Value, Profit Margin, Conversion Rate  

---

## 🧰 Tools & Technologies

- **Power BI Desktop** – for data visualization and dashboard creation  
- **DAX (Data Analysis Expressions)** – for calculated measures and KPIs  
- **Power Query** – for data cleaning and transformation  
- **Excel / CSV Datasets** – as data sources  

---

## 🔗 Data Model Overview

The model connects these datasets:
1. **Sales** – Detailed sales data with revenue, quantity, and dates  
2. **Product** – Product categories and pricing information  
3. **Location** – Customer segmentation and location details
4. **Date Table** - The periods all transactions happened
6. **People** - Sales people and team


These tables are linked using **primary and foreign keys** (e.g., `ProductID`, `CustomerID`, `RegionID`) to ensure accurate aggregations.

---

## 📊 Insights & Use Cases

- Identify high-performing regions and products  
- Track monthly or quarterly revenue growth  
- Compare actual vs. target sales performance  
- Analyze sales representative contributions  
- Support management reporting and forecasting  

---

## 🖼️ Dashboard Preview

<img width="870" height="495" alt="image" src="https://github.com/user-attachments/assets/1f073e63-029c-4349-a63d-2d80f75c8e30" />

<img width="863" height="495" alt="image" src="https://github.com/user-attachments/assets/5ad50934-6418-4b3c-927d-9d75a7cb750d" />

---

## ⚙️ How to Use

1. Open the Power BI Desktop 
2. Load or connect your dataset if using custom data  
3. Refresh data to update visuals and KPIs  
4. Interact with filters and slicers for deeper insights  

---

## 📁 Repository Structure

