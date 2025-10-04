# 🛍️ Retail Sales Data Analysis – ShopTrendz (Case Study)

## 📌 Project Overview
This case study focuses on **sales data analysis for ShopTrendz**, a retail company selling electronics and fashion items across multiple cities in Pakistan.  
The project involves **data cleaning, exploratory analysis, and visualization** using Python to extract business insights and help executives make data-driven decisions.

---

## 🧭 Objectives
- Clean and preprocess 12 months of sales data.  
- Analyze sales performance by product, category, city, and month.  
- Visualize trends and KPIs to identify growth opportunities.  
- Summarize findings in a clear business report.

---

## 📂 Dataset
- **File:** `sales_data.csv`  
- **Columns:**  
  - `Order ID` (int)  
  - `Product Name` (string)  
  - `Category` (Electronics / Fashion)  
  - `City` (string)  
  - `Order Date` (dd-mm-yyyy)  
  - `Units Sold` (int)  
  - `Unit Price` (float)  
  - `Total Sales` (float)

---

## 🛠️ Tools & Libraries
- **Language:** Python  
- **Libraries:** pandas, numpy, matplotlib  
- **Environment:** Jupyter Notebook

---

## 🧹 Part 1 – Data Cleaning & Preparation
- Loaded dataset using Pandas and inspected structure.  
- Checked for and handled missing values.  
- Converted `Order Date` column to datetime format.  
- Extracted **Month** from the order date.  
- Calculated `Total Sales = Units Sold × Unit Price` (if not present).  

---

## 📊 Part 2 – Exploratory Data Analysis (EDA)
Performed key calculations to understand performance:

- 📝 **Basic Stats**  
  - Total number of orders  
  - Total revenue  
  - Average sales per order  
  - Top 5 best-selling products

- 📈 **Trend & Distribution Analysis**  
  - Monthly sales trends  
  - City-wise sales distribution  
  - Category-wise revenue comparison

---

## 📈 Part 3 – Data Visualization (Matplotlib)
The following visualizations were created for business insights:

1. **📅 Line Plot** – Monthly sales trend  
2. **🏆 Bar Chart** – Top 5 products by units sold  
3. **🥧 Pie Chart** – Category-wise revenue share  
4. **🌆 Horizontal Bar Plot** – City-wise total sales  

All plots include clear titles, axis labels, grids, and color formatting for readability.

---

## 📝 Part 4 – Business Report
A concise 1–2 page **PDF report** was prepared containing:

- **Introduction** → Overview of the dataset and goals.  
- **Analysis Summary** → Key insights from EDA.  
- **Visuals** → Screenshots of plots.  
- **Conclusion & Recommendations** → Practical business suggestions.

---

## 📌 Key Insights
- **Electronics** category contributed the highest share of total revenue.  
- Top-selling products were consistently from the **Electronics** category.  
- Major cities like **Karachi & Lahore** generated the most sales.  
- Sales peaked during festive months, indicating strong **seasonality trends**.

---

## 🚀 Business Recommendations
- 📦 **Stock Top Products** → Ensure high-demand electronics are always available.  
- 🏬 **City-wise Strategy** → Focus marketing efforts on high-performing cities.  
- 🛍️ **Seasonal Campaigns** → Launch targeted promotions during peak months.  
- 🧠 **Category Diversification** → Boost fashion category sales through bundles or discounts.

---
