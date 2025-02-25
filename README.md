# 📊 Power BI Sales Dashboard

### 🚀 **Overview**
This **Power BI dashboard** provides a comprehensive analysis of sales data, helping businesses track performance, optimize operations, and make data-driven decisions. It includes key insights into **top-selling products, sales trends, customer behavior, and shipping performance**.

---

## 📌 **Features**
✅ **Top-Selling Products** – Identifies the best-performing items.  
✅ **Sales Performance Analysis** – Tracks revenue and order trends over time.  
✅ **Geographical Sales Distribution** – Visualizes sales across different regions.  
✅ **Average Shipping Time** – Calculates time between order and shipment using DAX.  
✅ **Interactive Filters & Drill-throughs** – Allows deeper exploration of data.  

---

## 🛠 **Technologies Used**
- **Power BI** – For data visualization and interactive reporting.  
- **DAX (Data Analysis Expressions)** – Used for calculated columns and measures.  
- **Data Cleaning & Transformation** – Performed within Power Query.  

---

## 🔢 **DAX Calculation Example**
To calculate the **average shipping time**, the following DAX formula was used:  

```DAX
Shipping_Time_Days = DATEDIFF('Sales'[Order Date], 'Sales'[Ship Date], DAY)
