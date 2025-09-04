RetailPulse – Sales Performance & Customer Insights Dashboard

RetailPulse is a comprehensive business intelligence project that analyzes retail sales and customer behavior using the Superstore dataset. The project covers data cleaning, modeling, DAX calculations, and interactive dashboarding in Power BI to deliver actionable insights for business leaders.

👥 Team Members
Name	Role	Responsibilities
Vaibhav Pandey	Team Leader	Data Cleaning, Modeling, Dashboarding
📊 Project Overview

The project focuses on analyzing various retail attributes such as:

Sales, Profit, and Quantity trends

Customer segmentation and contribution

Category and sub-category performance

Regional and city-wise analysis

Discount impact on profitability

The ultimate goal is to empower retail managers with insights for growth, efficiency, and profitability.

🧹 Data Cleaning & Preparation

Performed in Power Query:

Removed null and invalid rows

Changed data types (dates, numeric columns)

Split customer names for flexibility

Created DimDate table for time intelligence

Renamed queries and structured into Mart (fact table) and supporting dimensions

🏗️ Data Modeling

Implemented a Star Schema with Mart as the fact table

Created relationships between DimDate, Customers, Products, and Regions

Ensured referential integrity for clean analysis

📐 DAX Measures

Key measures created:

Basic: Total Sales, Total Profit, Total Quantity, Distinct Customers, Avg Discount

Time Intelligence: YTD Sales, Previous Year Sales, YoY Growth %

Advanced: Customer Contribution %, Profitability under high discounts, Regional performance comparisons

📈 Dashboard Features

Designed in Power BI with:

KPI Cards: Sales, Profit, Quantity, Customers, Discounts, Growth %

Visuals: Bar charts, Line charts, Maps, Funnel, Matrix

Filters/Slicers: Region, Segment, Category, Sub-Category, Year

Drilldowns: City → State → Region analysis

Advanced Features: Bookmarks for toggle views, Heatmaps for sales density

🖼️ Dashboard Preview

Here are sample snapshots of the Power BI dashboard:

Overview Dashboard


Regional & Customer Insights


Category & Profitability Analysis


👉 Replace images/... with the actual screenshot paths once you upload them to your repo.

💡 Key Insights

Certain categories drive sales but hurt profitability due to high discounts.

The West region consistently outperforms others in revenue.

A small % of top customers contribute disproportionately to total sales.

Profitability is strongly seasonal with peaks in Q4.

Repeat customers account for a significant share of sales.

📁 Repository Structure
RetailPulse/
│── RetailPulse.pbix              # Power BI project file
│── Sample - Superstore.csv       # Original dataset
│── images/                       # Folder for dashboard screenshots
│── README.md                     # Project documentation

🧰 Tools & Technologies Used

Power BI (Data Modeling, DAX, Visualizations, Dashboarding)

Power Query (Data Cleaning & Transformation)

Excel/CSV (Raw dataset)

Git & GitHub (Version control & collaboration)

📫 Contact

For queries or collaboration, feel free to connect:

Vaibhav Pandey: GitHub
 | LinkedIn
