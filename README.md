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
![Data Model](Sales Project using Excel/Screenshot13.png?raw=true)

---

## 📈 Dashboard Preview  
<img src="https://github.com/your-username/your-repo/blob/main/assets/dashboard-1.png?raw=true" width="1000">
<img src="https://github.com/your-username/your-repo/blob/main/assets/dashboard-2.png?raw=true" width="1000">

---

## 🎥 Project Demo  
<img src="https://github.com/your-username/your-repo/blob/main/assets/demo.gif?raw=true" width="1000">

---

## 🔍 Key Insights
1. **Insight #1**: [e.g., Certain products contribute disproportionately to total revenue]  
2. **Insight #2**: [e.g., Seasonal peaks identified in sales trends]  
3. **Insight #3**: [e.g., Loyal customer segments revealed through repeat orders]  
4. **Insight #4**: [e.g., Some regions underperform despite high customer count]  
5. **Insight #5**: [e.g., Inventory challenges during promotional periods]  

---

## 💡 Conclusion  
This Excel dashboard project demonstrates how powerful insights can be generated using only Excel tools. It helps stakeholders track KPIs, discover hidden patterns, and improve decision-making without relying on external BI tools.

---

## 🧰 Tools Used
- **Microsoft Excel**  
- **PivotTables & Charts**  
- **Conditional Formatting**  
- **Excel Formulas (e.g., SUMIFS, VLOOKUP/XLOOKUP)**  
- **Data Validation & Slicers**
