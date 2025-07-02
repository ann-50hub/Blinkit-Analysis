**# Blinkit Analysis**
-----------------------
Real Time Power Bi Project

Project Overview

The Blinktit Data-Analysis project is a Power BI report developed to analyze business data from an Excel file. The dashboard provides insightful KPIs and visualizations to support strategic decision-making.

This project includes data transformation, modeling, and DAX-based calculations to meet specific business requirements and track key performance indicators.



Tools & Technologies Used

1.Power BI Desktop

2.Power Query

3.DAX (Data Analysis Expressions)

4.Microsoft Excel (CSV Source)

5.GitHub (Version Control)

Source Data

1.Data Source: Excel file (BlinkIT.csv)

2.Import Mode: Import directly into Power BI Desktop

3.Tables Included: 

*Item Fat Content

*Item Identifier	

*Item Type	

*Outlet Establishment Year	

*Outlet Identifier	

*Outlet Location Type

*Outlet Size	

*Outlet Type

*Item Visibility	

*Item Weight



 Business Requirements

 
The report was developed to satisfy the following business needs:

*Track Overall Sales Performance

*Monitor Product Volume Sold

*Assess Customer Satisfaction

*Evaluate Sales Efficiency


KPI's Requirements

*Total Sales: The overall revenue generated from all items sold

*Average Sales: The average revenue per sale

*Number Of Items: The total count of different items sold

*Average Rating: The average customer rating for items sold


 Project Workflow:

1.Requirement Gathering/Business:- Requirements Understanding stakeholder goals and data needs 

2.Data Walkthrough:-Initial assessment of dataset fields and structure  

3.Data Connection:-Connected Excel file using import mode 

4.Data Cleaning/Quality Check:-Normalized categorical values (e.g., `LF`, `low fat` → `Low Fat`)

5.Data Modeling

6.Data Processing:-Performed in Power Query 

7.DAX Calculations:-Custom measures created for dynamic KPIs  

8.Dashboard Layouting:-Designed user-friendly layout with slicers  

9.Charts Development and Formatting:-Built charts and graphs using best practices  

10.Dashboard/Report Development

11.Insight Generation:-Final report prepared for stakeholder presentation  

Sample DAX  Measures

 ```Avg Sales = AVERAGE('BlinkIT Grocery Data'[Sales])``` 

 🖼️ Dashboard Preview

KPI Cards: Shows the Total sales, Average Sales,Number of Items and Average Rating.

Interactive Filters for Outlet Size, Type, and Location

Pie and Bar Charts: Sales Analysis by item category, fat content, and fat by outlet type

Line Graph: Outlet Performance trends over establishment years

Business Insights

Sales Insights

*Total Sales reached $1.20M, indicating strong revenue performance.

*Average Sales per item is $141, suggesting healthy product-level profitability.

*Tier 3 locations lead with $472.13K in sales.

*Supermarket Type1 is the top contributor with $787.55K in sales.

 Product Insights

*Fruits and Vegetables & Snack Foods are top sellers (~$180K each).

*Low-performing categories include Seafood and Breakfast.

*Regular fat content items dominate sales ($776.32K), while Low Fat items show strong performance as well ($425.36K).

 Outlet Insights

*Medium-sized outlets generate the highest revenue ($507.90K).

*Outlets established around 2018–2019 peaked at $205K sales.




# 🚀 Blinkit Data Analysis

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow?logo=powerbi)
![Status](https://img.shields.io/badge/status-Completed-brightgreen)

![GitHub Repo stars](https://img.shields.io/github/stars/yourusername/blinkit-data-analysis?style=social)

> **Real-Time Power BI Dashboard Project for Business Intelligence & Data Storytelling**

---

## 📊 Project Overview

The **Blinkit Data Analysis** project uses **Power BI** to visualize and analyze business data from an Excel source. It enables decision-makers to understand sales, product performance, and customer behavior through KPIs and interactive charts.

---

## 🛠️ Tools & Technologies

- 🟡 Power BI Desktop  
- 🔍 Power Query  
- 🧠 DAX (Data Analysis Expressions)  
- 📄 Microsoft Excel (CSV format)  
- 🧬 GitHub (Version Control)

---

## 🗂️ Source Data

- **Data Source**: `BlinkIT.csv` (Excel file)  
- **Import Method**: Import mode into Power BI  
- **Tables Included**:
  - Item Fat Content
  - Item Identifier
  - Item Type
  - Outlet Establishment Year
  - Outlet Identifier
  - Outlet Location Type
  - Outlet Size
  - Outlet Type
  - Item Visibility
  - Item Weight

---

## 🧾 Business Requirements

The dashboard was developed to meet the following needs:

- 📈 Track overall sales performance  
- 📦 Monitor product volume sold  
- 🙂 Assess customer satisfaction  
- ⚙️ Evaluate sales efficiency

---

## 🔑 KPI Requirements

| KPI                                  | Description                                   |
|------------------|-----------------------------------------------|
| 💰 Total Sales    | Overall revenue from all items                |
| 📊 Average Sales  | Revenue per sale                              |
| 📦 Number of Items | Count of different items sold                |
| ⭐ Average Rating  | Customer satisfaction average (if available) |

---

## 🔄 Project Workflow

1. 📋 **Requirement Gathering** – Understanding stakeholder goals  
2. 🧾 **Data Walkthrough** – Review fields & structure  
3. 🔗 **Data Connection** – Connect CSV in Power BI  
4. 🧹 **Data Cleaning** – Normalize categories (e.g., `LF` → `Low Fat`)  
5. 🧩 **Data Modeling** – Define relationships and hierarchies  
6. 🔄 **Data Processing** – Transformations in Power Query  
7. 📐 **DAX Measures** – Custom KPIs & logic  
8. 🧱 **Dashboard Layout** – User-friendly, with slicers  
9. 📊 **Charts Development** – Visuals based on best practices  
10. 📝 **Report Creation** – Finalized dashboard  
11. 📡 **Insights Generation** – For stakeholders

---

## 📈 Sample DAX Measure

<pre>```DAX
Avg Sales = AVERAGE('BlinkIT Grocery Data'[Sales])</pre>



## 🖼️ Dashboard Review
 

- 📑**KPI Cards**: Shows the Total sales, Average Sales,Number of Items and Average Rating.

- ⌛**Interactive Filters**  For Outlet Size, Type, and Location

- 🥧 **Pie Charts and Bar Charts**: Sales Analysis by item category, fat content, and fat by outlet type

- 📈**Line Graph**: Outlet Performance trends over establishment years

## 📌 Business Insights

### 💰 Sales Insights


Total Sales: $1.20M — Indicating strong revenue performance.

Average Sales per Item: $141 — Reflects healthy product-level profitability.

### 🌍 Location Insights


🥇 Top Tier: Tier 3 Locations led with $472.13K in sales.

🏬 Best Performing Store Type: Supermarket Type1 — $787.55K in sales.

### 🛒 Product Insights


#### 🍎 Top Selling Categories:

Fruits and Vegetables (~$180K)

Snack Foods (~$180K)

#### 🐟 Low Performing Categories:

Seafood

Breakfast

### 🧈 Fat Content Trends:

Regular Fat Items: $776.32K

Low Fat Items: $425.36K

### 🏢 Outlet Performance

📏 Outlet Size: Medium-sized outlets generated the highest revenue — $507.90K.

### 🗓️ Establishment Year:

Outlets established around 2018–2019 peaked at $205K in sales.





