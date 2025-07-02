




# 🚀 Blinkit Data Analysis

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow?logo=powerbi)
![Status](https://img.shields.io/badge/status-Completed-brightgreen)



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
| ⭐ Average Rating  | Customer satisfaction average  |

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

- ![KPI Cards]https://github.com/ann-50hub/Blinkit-Analysis/blob/main/kpi-cards.png?raw=true)

- ⌛**Interactive Filters**  For Outlet Size, Type, and Location.

- ![Interactive Filters]https://github.com/ann-50hub/Blinkit-Analysis/blob/main/interactive%20filters.png?raw=true)

- 🥧 **Pie Charts and Bar Charts**: Sales Analysis by item category, fat content, and fat by outlet type

- 📈**Line Chart**: Outlet Performance trends over establishment years.
  
- ![Line Chart]https://github.com/ann-50hub/Blinkit-Analysis/blob/main/line%20charts.png?raw=true)

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





