Amazon Sales Data Analysis and Business Intelligence Dashboard
(Using Microsoft Excel & Power BI)
________________________________________
1️⃣ Project Overview
🎯 Business Problem
The primary goal of this project was to analyze Amazon sales performance data to identify trends, profitability patterns, and customer behavior insights. The business problem focused on: “Understanding sales performance, discount impact, and customer segmentation to improve profitability and strategic decision-making.”
Many regions showed high sales but low profits due to excessive discounting. The company needed a data-driven solution to:
•	Identify high-performing product categories
•	Analyze the impact of discounts on profit
•	Understand customer segments
•	Improve regional sales strategy
•	Support management with an interactive dashboard
This project transforms raw sales data into actionable business intelligence.
________________________________________
2️⃣ 🗂️ Data Source
📌 Source:
Company Database (Exported to Excel)
📁 Dataset:
Amazon Sales Dataset (2023–2025)
📊 Size:
•	10,0,0+ transaction records
•	15+ attributes


🔑 Key Variables:
Column Name	Description
Order ID	Unique order identifier
Order Date	Date of purchase
Ship Date	Date of shipping
Customer Name	Customer identifier
Segment	Consumer / Corporate / Home Office
Region	Sales region
Category	Product category
Sub-Category	Product sub-category
Sales	Total revenue
Quantity	Units sold
Discount	Discount applied
Profit	Profit earned
Payment Mode	Mode of payment
The dataset contains detailed transactional sales data across regions, categories, and customer segments.
________________________________________
3️⃣ 🛠️ Tools & Technologies
Component	Technology Used
Language	DAX (Data Analysis Expressions)
Database	Microsoft Excel
Visualization	Microsoft Excel 2025, Power BI 2024
Documentation	 Microsoft Word


🔧 Excel
•	Data cleaning
•	Removing duplicates
•	Formatting data types
•	Pivot tables
•	Feature engineering
📊 Power BI
•	Data modeling (Fact & Dimension tables)
•	DAX calculations
•	Interactive dashboards
•	Slicers and drill-down reports
________________________________________
4️⃣ 🧹 Data Cleaning & Preparation
Before analysis, several preprocessing steps were performed:
✔️ Handling Missing Values
•	Checked for null values
•	Replaced missing values where necessary
•	Removed incomplete records
✔️ Removed Duplicates
•	Identified duplicate Order IDs
•	Removed redundant records
✔️ Data Type Formatting
•	Converted Order Date and Ship Date to Date format
•	Converted Sales, Profit, Discount to Decimal
•	Ensured Quantity as Integer



✔️ Feature Engineering (New Calculated Columns)
1.	Profit Margin
Profit Margin = Profit / Sales
2.	Discount Percentage
Discount % = Discount * 100
3.	Shipping Duration
Ship Date – Order Date
4.	Year & Month Extraction
Used for trend analysis.
________________________________________
5️⃣ 🔍 Exploratory Data Analysis (EDA)
Main Questions Explored:
1.	📈 What is the overall sales trend?
2.	📊 Which region generates the highest revenue?
3.	🛒 Which product category performs best?
4.	💰 How does discount impact profit?
5.	👥 Which customer segment contributes most revenue?
6.	📉 Is there a correlation between price and customer rating?
________________________________________
📌 Example Key Visualization (Insert Screenshot Here)
👉 Insert screenshot of:
•	“Sales by Region” chart OR
•	“Profit vs Discount” scatter plot
This makes your report visually attractive.
________________________________________
6️⃣ 💡 Key Insights
•	🔹 Insight 1: Sales peaked during Q4, mainly due to seasonal promotions.
•	🔹 Insight 2: Consumer segment contributes the highest revenue share.
•	🔹 Insight 3: Higher discounts significantly reduce profit margins.
•	🔹 Insight 4: Technology and Office Supplies categories generate stable profits.
•	🔹 Insight 5: A small group of products contributes to most of the revenue (Pareto effect).
________________________________________
7️⃣ 🚀 Recommendations
Based on the analysis:
📌 1. Optimize Discount Strategy
Avoid excessive discounting in high-sales regions to protect margins.
📌 2. Focus on High-Profit Categories
Increase inventory and marketing for:
•	Technology
•	Office Supplies
📌 3. Target Consumer Segment
Develop loyalty programs for Consumer segment to increase repeat purchases.
📌 4. Reduce Revenue Dependency
Promote underperforming products to diversify revenue sources.
📌 5. Improve Regional Pricing Strategy
Re-evaluate pricing in low-profit regions.
________________________________________
8️⃣ ⚙️ How to Use This Project
📥 Requirements
•	Microsoft Excel 2025
•	Power BI Desktop 2024
•	Microsoft Word (for documentation)
________________________________________


📌 Steps to Run:
1.	Open the Excel dataset.
2.	Perform data cleaning (if required).
3.	Load dataset into Power BI.
4.	Create relationships between:
o	Fact_Sales
o	Dim_Customer
o	Dim_Product
o	Dim_Location
o	Dim_Date
5.	Apply DAX measures.
6.	Use slicers for interactive filtering.
7.	Refresh data if new records are added.
________________________________________
📦 DAX Sample Measures
Total Sales = SUM(Fact_Sales[Sales])
Total Profit = SUM(Fact_Sales[Profit])
Profit Margin = DIVIDE([Total Profit], [Total Sales])
Average Discount = AVERAGE(Fact_Sales[Discount])
________________________________________
9️⃣ Conclusion
This project demonstrates how raw transactional sales data can be transformed into meaningful business intelligence using:
•	Microsoft Excel for data preparation
•	Power BI for visualization
•	DAX for advanced calculations
The dashboard enables management to:
•	Monitor sales performance,Identify profit drivers,Detect high discount impact,Make strategic business decisions
Overall, this project proves the power of combining Excel and Power BI for real-time, data-driven decision-making.
