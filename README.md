🚀 RetailPulse – Sales Performance & Customer Insights Dashboard

RetailPulse is a comprehensive business intelligence project that analyzes retail sales and customer behavior using the Superstore dataset.
The project covers data cleaning, modeling, DAX calculations, and interactive dashboarding in Power BI to deliver actionable insights for business leaders.

👥 Team Members
Name	Role	Responsibilities
Vaibhav Pandey	Team Leader	Data Cleaning, Modeling, Dashboarding
📊 Project Overview

This project explores retail operations to uncover:
✔️ Sales, Profit, and Quantity trends
✔️ Customer segmentation & contribution
✔️ Category & Sub-category performance
✔️ Regional & City-wise insights
✔️ Discount impact on profitability

🎯 Goal: Empower retail managers with data-driven insights for growth, efficiency, and profitability.

🧹 Data Cleaning & Preparation

Performed in Power Query:

🗑️ Removed null and invalid rows

🔄 Changed data types (dates, numeric columns)

✂️ Split customer names for flexibility

📅 Created DimDate table for time intelligence

📂 Structured into Mart (fact table) & supporting dimensions

🏗️ Data Modeling

⭐ Implemented a Star Schema with Mart as fact table

🔗 Built relationships between DimDate, Customers, Products, Regions

✅ Ensured referential integrity for clean analysis

📐 DAX Measures

Key measures include:

Basic

Total Sales, Total Profit, Total Quantity, Distinct Customers, Avg Discount

Time Intelligence

YTD Sales, Previous Year Sales, YoY Growth %

Advanced

Customer Contribution %

Profitability under high discounts

Regional performance comparisons

📈 Dashboard Features

🔹 Designed in Power BI with:

📊 KPI Cards: Sales, Profit, Quantity, Customers, Discounts, Growth %

📉 Visuals: Bar charts, Line charts, Maps, Funnel, Matrix

🎛️ Filters/Slicers: Region, Segment, Category, Sub-Category, Year

🔍 Drilldowns: City → State → Region analysis

✨ Advanced Features: Bookmarks toggle & Heatmaps

🖼️ Dashboard Preview

📌 Sample snapshots of the Power BI dashboard:

🔹 Overview Dashboard

🔹 Regional & Customer Insights

🔹 Category & Profitability Analysis

👉 (Add screenshots in an /images folder and update links above)

💡 Key Insights

✅ Certain categories drive sales but hurt profitability due to high discounts
✅ The West region consistently outperforms others in revenue
✅ A small % of top customers contribute disproportionately to sales
✅ Profitability is seasonal with peaks in Q4
✅ Repeat customers account for a significant share of revenue

📁 Repository Structure
RetailPulse/
│── RetailPulse.pbix              # Power BI project file
│── Sample - Superstore.csv       # Original dataset
│── images/                       # Dashboard screenshots
│── README.md                     # Project documentation

🧰 Tools & Technologies

Power BI – Data Modeling, DAX, Visualizations

Power Query – Data Cleaning & Transformation

Excel/CSV – Raw dataset

Git & GitHub – Version control & documentation

📫 Contact

💡 For queries or collaboration, feel free to connect:

Vaibhav Pandey
🔗 GitHub
 | 🔗 LinkedIn
