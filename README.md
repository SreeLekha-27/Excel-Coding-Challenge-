# E-Commerce Sales Analysis Dashboard

## Project Overview
This project focuses on cleaning, analyzing, and visualizing a large e-commerce sales dataset using **Microsoft Excel**. The goal is to generate insights from raw sales data, identify trends, and create an interactive dashboard to support business decisions.  

The dataset contains **51,290 rows and 13 columns** including order details, customer information, product categories, and financial metrics like **Sales, Quantity, Discount, and Profit**.  

---

## Dataset Description
- **Columns:** Order ID, Customer Name, Order Date, Ship Date, Region, Country, Category, Sub-Category, Product Name, Sales, Quantity, Discount, Profit.  
- **Missing Values:** Significant missing data in columns such as Order ID, Customer Name, Sales, Discount, and Profit.  
- **Data Type Issues:** Most numeric columns (Sales, Quantity, Discount, Profit) are stored as text/object and need conversion.  
- **Duplicates:** No duplicates found.  
- **Categorical Data:** Columns like Region, Category, and Sub-Category are mostly complete and reliable for analysis.  

---

## Data Cleaning Steps
1. **Convert raw data into proper Excel tables** to enable filtering and calculations.  
2. **Remove rows with missing Order IDs**, as these rows also have multiple critical missing fields.  
3. **Correct Date Format**: Convert Order Date and Ship Date to proper Excel date format.  
4. **Handle Missing Values**:  
   - Customer Name: Replace blank cells with `"Unknown Customer"`.  
   - Sales, Discount, Profit: Replace blanks with the column's average value.  
5. **Convert numeric columns** (Sales, Quantity, Discount, Profit) from text/object to numeric for calculations.  

---

## Pivot Tables Created
1. **Sales & Profit by Category**  
2. **Top Products by Sales/Profit**  
3. **Sales by Region/Country**  
4. **Monthly/Yearly Sales Trend**  
5. **Discount vs. Profit Analysis**  

---

## Dashboard Features
### Key Metrics Cards
- Total Sales  
- Total Profit  
- Total Orders  
- Growth %  

### Charts
- **Line Chart:** Monthly/Yearly Sales Trend  
- **Pie Chart:** Profit by Category  
- **Bar Chart:** Top 10 Products by Sales/Profit  
- **Clustered Column & Line Chart:** Country-wise sales by Category  

### Insights Box
- Last month growth is slightly negative at **-3.96%**.  
- **Office Supplies** category contributes the largest share of profit.  

### Interactivity
- **Slicers** for Category, Region, Month/Year to make the dashboard interactive.  
- Charts are linked to pivot tables, updating dynamically when slicers change.  

---

## Tools Used
- Microsoft Excel (Pivot Tables, Formulas, Charts, Slicers)  

---

## Key Learnings
- Efficient handling of missing and inconsistent data in large datasets.  
- Creating meaningful KPIs and visualizations from raw e-commerce data.  
- Building an interactive Excel dashboard to support business decision-making.  

---

## Repository Structure
