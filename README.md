# Blinkit Data-Analysis
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


Dashboard Review

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

  















