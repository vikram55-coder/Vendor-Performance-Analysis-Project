# Vendor-Performance-Analysis-Project
This project performs a complete data analysis on vendor purchase and sales performance using Python (Pandas, Matplotlib) SQL (SQLite3) and Power Bl. The goal is to identify top vendors, high-margin low-sales products, freight inefficiencies, and optimize inventory decisions.

roject Overview

Dataset  Multiple CSVs (Vendor Sales)
Tools: Python, Pandas, SQLite3, Power BI
Techniques Used**:
 Data Cleaning & KPI Calculation (Python)
 Business Questions Solved (12 Questions)
 SQL Querying on Live Data Table using `sqlite3` + `pandas.read_sql_query`
 Visualizations (Bar chart, Pie chart, Correlation etc.)
 Power BI Dashboard with interactive visuals and KPI cards

Key Business Questions Solved

| # | Question |

| Q1 | Top 5 Vendors by Sales 
| Q2 | Vendors with Negative Profit Margin
| Q3 | Vendors with Highest Freight per Unit 
| Q4 | Correlation between Purchase & Sales Quantity 
| Q5 | Vendors with Stock Turnover < 1 
| Q6 | Total Unsold Inventory Value 
| Q7 | Top Brands by Sales to Purchase Ratio 
| Q8 | Average Profit Margin by Brand 
| Q9 | Vendor Contribution to Sales (Top 5) 
| Q10 | High Margin but Low Sales Vendors 
| Q11 | Vendors with Purchases but Zero Sales 
| Q12 | Top Brands by Gross Profit 


KPIs Calculated

Gross Profit = Sales - Purchase
Profit Margin (%)
Freight Per Unit = Freight / Sales Quantity
Stock Turnover = Sales Quantity / Purchase Quantity
Sales to Purchase Ratio


ools Used

 Python: Data cleaning, transformation, KPI generation
QLite3: SQL queries for real-time data insights
 andas: Query execution, grouping, filtering
 atplotlib: Bar, pie, trend charts
 Power BI: Dashboard for management-level visuals


Power BI Dashboard
 Key Insights:
Total Sales**: $451.62M
Total Purchases**: $321.90M
Gross Profit**: $129.72M
Excise Tax Paid**: $18.97M
Top Vendors**: Diageo North America, Martignetti, Bacardi
low Performers**: Flavor Essence, Ira Goldman, Laurate Imports

 Visuals:
🔘 Purchase Contribution % (Donut Chart)
 📶 Top Vendors by Sales (Bar Chart)
📈 Top Brands by Sales (Waterfall Chart)
 🔻 Low Performing Vendors
 🎯 Vendor Profitability (Scatter Plot)

<img width="871" height="489" alt="vendor_deshbord" src="https://github.com/user-attachments/assets/b973c307-1a9a-43b1-8dda-0b921f86d46b" />

 
