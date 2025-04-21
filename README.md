 # 📊 Mobile Sales Dashboard 
This project features an interactive Power BI dashboard that provides a comprehensive analysis of mobile sales data. The dashboard includes multiple pages with key metrics and visuals such as:

Total Sales, Quantity, and Transactions

Sales Trends by Month, Day, and City

Sales Comparison by Brand and Mobile Model

Customer Ratings Analysis

Transaction Breakdown by Payment Method

MTD (Month-to-Date) Performance by Year, Quarter, Month, and Day

Year-over-Year Sales Comparison

The visualizations offer actionable insights for business performance tracking and decision-making in the mobile sales domain.
# Tools Used
Power BI Desktop – For building visual reports and dashboards

Microsoft Excel – For initial data preparation and formatting

DAX (Data Analysis Expressions) – To create calculated columns and custom measures

Power Query Editor – For data cleaning, transformation, and loading

OpenStreetMap (Power BI Map Visual) – For geospatial sales representation

Slicers & Filters – For dynamic interaction and drill-downs
# Dashboard Highlights
Key Metrics:

Total Sales: 769M

Quantity Sold: 19K

Transactions: 4K

Average Price: 40.11K

Sales Breakdown:

By City, Brand, and Mobile Model

Over Month, Day of Week, and Year

Customer Ratings by Status (Good, Average, Poor)

Transaction Modes: UPI, Debit Card, and Credit Card

MTD (Month-to-Date) analysis by Year, Quarter, Month, and Day

Year-over-Year Comparisons for better performance tracking
# Process Steps
# 1. Data Collection
Data collected includes mobile brand, model, quantity sold, total sales, transaction count, payment method, ratings, date, and city.

# 2. Data Cleaning (in Power Query)
Removed nulls, handled data types, filtered incomplete entries

Merged and transformed tables where needed

Renamed columns for clarity

# 3. Data Modeling
Defined relationships between tables (e.g., Date, Sales, Product, Region)

Set up a proper star schema for efficient querying

# 4. DAX Calculations
Created calculated columns and measures such as:

Total_Sales, Total_Quantity, Average_Price, Transaction_Count

Month-to-Date (MTD) and Year-over-Year comparisons

# 5. Report Building
Designed multiple interactive report pages:

Main Dashboard: KPIs, total sales by city/month, sales by brand/model, day-wise analysis

MTD Dashboard: Trends by year, quarter, month, and day

Year-over-Year Comparison: Sales vs. same period last year by year, quarter, and month

# 6. Visualization
Used bar charts, line charts, pie charts, map visuals, and slicers for interactivity

Applied clean, user-friendly layout and consistent color theme


