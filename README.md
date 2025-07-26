# 📊 Sales Project – Excel Dashboard

### 🔗 [My LinkedIn](https://www.linkedin.com/in/abdulrahman-ahmed66)
### 📥 [Download the Excel File](Sales_Project.xlsx?raw=true)

<br>
<div align="center">
  <img src="Sales Project using Excel/Screenshot (10).png?raw=true" alt="Dashboard Banner" width="1000" height="500">
</div>

---

## 📝 Introduction
<details>
  <summary><strong>📌 Overview (click)</strong></summary>

### **Overview**  
> This Excel project focuses on analyzing sales data from 2015 to 2018 to uncover key business insights and trends.  
> Using Excel's advanced tools such as Power Query, Power Pivot, and PivotTables, the project transforms raw multi-year data into a dynamic and interactive dashboard.  
> It provides a clear view of sales performance, top-selling products, and patterns that support data-driven decision-making.

</details>

<details>
  <summary><strong>📂 Data Sources (click)</strong></summary>

### **Data Sources**  
> The project is based on a structured data model consisting of **three main tables**:

1. **Fact Sales Table**  
   - Contains transactional data from 2015 to 2018  
   - Key Columns: `Order ID`, `Order Date`, `Customer ID`, `Product ID`, `Quantity`, `Unit Price`, `Total Sales`

2. **Product Table**  
   - Describes each product with its attributes  
   - Key Columns: `Product ID`, `Product Name`, `Category`, `Cost`

3. **Customer Table**  
   - Contains customer information and segmentation  
   - Key Columns: `Customer ID`, `Customer Name`, `Segment`, `Region`

> The data was cleaned and transformed using Power Query, and relationships were built between tables using Power Pivot to enable advanced analysis.
</details>

---

## 🎯 Case Study  
This project simulates a real-world business scenario where a company needed to analyze historical sales data spread across multiple Excel sheets from 2015 to 2018.

The original data was fragmented, inconsistent, and difficult to analyze. To solve this, I used Power Query to append all sheets into a single dataset, applied data cleaning techniques to ensure accuracy, and built relationships using Power Pivot.

The goal was to create an interactive Excel dashboard that allows stakeholders to:
- Track sales performance over four years  
- Compare year-over-year trends  
- Identify top-performing products and regions  
- Understand seasonal or monthly patterns in sales  
- Make data-driven decisions in sales, inventory, and marketing strategies
- ...I used Power Query to append all sheets into a single dataset, applied data cleaning techniques to ensure accuracy, and built a data model consisting of fact and dimension tables (Sales, Product, Customer) using Power Pivot.

This case study demonstrates how Excel can be a powerful tool for business intelligence, even without external BI software.  

---

## 📊 Main KPIs

- **💰 Total Sales** – 2.29M  
- **📦 Total Quantity Sold** – 38K units  
- **🧾 Total Orders** – 5003  
- **🏆 Top 10 Customers by Sales** – Based on total revenue  
- **🕒 Monthly Sales Trends** – Line chart showing sales quantity by month   
- **📍 Sales by Region** – Sales split across West, East, Central, South  
- **💲 Average Discount Applied** – 16%


---

## ⚙️ Process

1. **Data Aggregation**  
   - Collected sales data from 2015 to 2018 and combined it using Power Query (Append Queries)

2. **Data Cleaning**  
   - Removed blanks, handled data types, and ensured consistency across all columns

3. **Data Modeling**  
   - Created relationships between the Fact Table and Dimension Tables (Product and Customer) using Power Pivot

4. **KPI Calculation**  
   - Created calculated columns and measures (e.g., Total Sales, Total Profit, Avg. Discount)

5. **Dashboard Design**  
   - Built Pivot Tables and Charts  
   - Used slicers for interactivity (Year, Region, Category, Segment)  
   - Organized the layout in a clean, user-friendly dashboard sheet

---

## 📐 Data Structure  
![Data Model](Sales%20Project%20using%20Excel/Screenshot13.png?raw=true)

---


## 🔍 Key Insights
1. **Top-performing products** like *Tables* and *Chairs* contributed significantly to overall revenue across the years.
2. **Monthly sales trends** revealed seasonal peaks, especially during Q4 of each year.
3. **High-value customers** were identified based on frequent orders and larger purchase amounts.
4. The **Consumer segment** showed the highest engagement compared to Corporate and Home Office segments.
5. **Regional analysis** highlighted strong performance in the *West* region in terms of both orders and revenue.

---

## 💡 Conclusion
This Excel project demonstrates the power of using Excel's built-in tools—such as **Power Query**, **PivotTables**, **Power Pivot**, and **Dashboard Design**—to perform in-depth data analysis.

By consolidating and analyzing sales data from 2015 to 2018, the final dashboard delivers valuable business insights, helping stakeholders monitor performance, identify opportunities, and make data-driven decisions—all without relying on external BI platforms.
