# Inventory-Insight-Dashboard# 📦 Inventory Insight Dashboard (Power BI)

## 🔍 Overview
The **Inventory Insight Dashboard** provides a real-time view of stock movement, turnover, and product performance across categories.  
It helps warehouse managers, supply chain planners, and business analysts to **optimize inventory**, **reduce holding costs**, and **improve stock availability** using interactive visuals built in Power BI.

---

## ⚙️ Tools & Technologies
- Power BI Desktop  
- Power Query (ETL)  
- DAX (Data Analysis Expressions)  
- Excel / CSV Data Sources  
- KPI Cards, Gauges, Pie Charts & Bar Visuals  

---

## 🎯 Key Objectives
1. Monitor **Total Stock Quantity** and **Stock Value**  
2. Track **Inventory Turnaround Ratio** to measure efficiency  
3. Compare **Actual vs Recorded Quantity** for accuracy  
4. Visualize **Sales by Month** for trend analysis  
5. Analyze **Category-wise Inventory Distribution**  
6. Identify **Product Status** (Active, Backordered, or Discontinued)  

---

## 🧠 Business Insights
- **Total Quantity of Stock:** 55K units  
- **Value of Holding Stock:** $332.65K  
- **Total Revenue:** $344K  
- **Inventory Turnaround Ratio:** -2.8, indicating potential overstocking or negative turnover efficiency  
- **Fruits & Vegetables ($86.03K)** and **Beverages ($62.94K)** dominate category sales  
- **Discontinued and Backordered items (~325–333)** suggest the need for improved demand forecasting  
- **Average Shelf Life: 0.19**, showing fast-moving inventory cycles in some categories  

---

## 📈 Dashboard Features

| Feature | Description |
|----------|-------------|
| **KPI Cards** | Key metrics for stock quantity, stock value, revenue, and shelf life |
| **Gauge Chart** | Displays the Inventory Turnaround Ratio for performance tracking |
| **Bar Charts** | Monthly sales and actual vs recorded quantity comparisons |
| **Pie Charts** | Visualize inventory distribution by category and product status |
| **Interactive Layout** | Users can easily filter or drill down into product-level insights |

---

## 🗂️ Data Model Overview
- **Fact Table:** `Inventory_Facts`  
- **Dimension Tables:** `Products`, `Categories`, `Dates`, `Status`  
- Relationships defined on `Product_ID` and `Category_ID`  
- DAX Measures created for:  
  - `Total Quantity`
  - `Total Stock Value`
  - `Inventory Turnaround Ratio`
  - `Average Shelf Life`
  - `Total Revenue`

---

## 📷 Dashboard Preview
https://github.com/chavdajaymeen-create/Inventory-Insight-Dashboard/blob/main/Inventory%20Dashboard.jpeg
![Inventory Dashboard](bded51a0-0658-44c9-8323-62e767719e5c.png)

