Project 1 - Supply chain dashboard
The objective of this project was to transform raw supply chain data into an interactive business intelligence dashboard that helps stakeholders quickly identify revenue drivers, profitable categories, customer behavior, and operational inefficiencies.
The dataset contains 180K+ supply chain records covering orders, customers, products, markets, shipping, sales, discounts, and profitability.

🗂️ Dataset Details
Order & Order Item details
Order Date
Customer Information
Customer Segment
Product & Category
Sales Amount
Product Price
Discount & Discount Rate
Order Profit
Order Quantity
Order Status
Shipping Mode
Scheduled & Actual Shipping Days
Customer Country & City
Order Country & Region
Market
Product Category & Sub-Category

🛠️ Tools & Technologies Used
Power BI – Dashboard development and visualization
DAX – Measures, KPIs and analytical calculations
Power Query – Data cleaning and transformation
Excel/CSV – Raw data source
Data Modeling – Fact and Dimension table structure
Microsoft Bing Maps – Geographical analysis

🔄 Data Cleaning & Transformation
Before building the dashboard, I performed several data preparation activities:
Removed duplicate and unwanted records
Handled missing and null values
Standardized data types
Cleaned product, customer and geographical information
Transformed date fields for time-based analysis
Prepared data for analytical reporting
Created calculated columns and measures using DAX

I also structured the model using Fact and Dimension tables, including:
Fact Orders
Dim Customer
Dim Date
Dim Location
Dim Product
Dim Shipping
This helped create a more organized and scalable reporting model.

🧠 Key Business Insights
Some important insights that can be derived from the dashboard include:
🔹 High sales do not necessarily mean high profitability.
A product or category may generate significant revenue while having lower profit because of discounts, product costs or operational expenses.
🔹 Product-level analysis can identify underperforming products.
Products generating very low revenue can be reviewed for pricing, promotion, inventory or discontinuation decisions.
🔹 Customer segmentation helps improve sales strategies.
Understanding Consumer, Corporate and Home Office behavior allows businesses to design targeted offers.
🔹 Shipping performance directly impacts customer experience.
Comparing planned and actual shipping times helps identify logistics problems.
🔹 Order-status analysis provides visibility into operational bottlenecks.
A high number of pending, processing or payment-related orders may indicate areas requiring operational attention.
🔹 Regional analysis helps identify growth opportunities.
Geographical sales patterns can be used to identify strong markets as well as regions requiring additional sales or marketing efforts.
🔹 Discounts should be evaluated alongside profitability.
Increasing sales through heavy discounts may not necessarily improve the company's bottom line.

📊 What’s Included in the Dashboard?
Page 1 – Sales Overview

✅ KPI cards for Sales, Profit, Orders and Quantity
✅ Monthly Sales Trend
✅ Sales by Customer Segment
✅ Sales by Order Region
✅ Shipping Mode Analysis
✅ Sales by Product Category
✅ Top Products by Sales
✅ Geographical Sales Map
✅ Interactive Year, Category and Region filters

Page 2 – Product & Operations Analysis

✅ Product-wise Sales Analysis
✅ Category-wise Profit Analysis
✅ Order Status Distribution
✅ Sales vs Discount Analysis
✅ Planned vs Actual Shipping Days
✅ Shipping Mode Performance
✅ Product and Shipping filters

📐 Concepts Applied
Data Cleaning
Data Transformation
Data Modeling
Star Schema
Fact & Dimension Tables
Relationships & Cardinality
DAX Measures
KPI Development
Time-Based Analysis
Customer Segmentation
Product Performance Analysis
Profitability Analysis
Regional Analysis
Logistics Analysis
Interactive Dashboard Design
Business Intelligence Reporting


PROJECT 2 -  EDA Dashboard
This project presents an interactive global sales performance dashboard designed to analyze revenue, profit, customer behavior, and market performance across multiple regions and product categories. The dashboard enables stakeholders to monitor KPIs, identify top-performing markets and products, and uncover profitability and customer retention insights.

🗂 Dataset Details
Order Date (Year-wise analysis)
Country & Market (APAC, EU, US, EMEA, LATAM, Africa, Canada)
Product Category & Sub-Category
Sales Revenue
Profit
Quantity Sold
Customer Type / Repeat Customer Indicator
Segment (Consumer, Corporate, Home Office)

🛠 Tools & Technologies Used
Power BI – Dashboard creation & visualization
DAX – Calculated measures (Profit %, KPIs, YoY comparison)
Power Query – Data cleaning and transformation
Microsoft Bing Maps – Geographical visualization
Excel / CSV – Data source

🔄 Data Processing & Modeling
Cleaned raw sales data using Power Query

Created relationships between:
Orders
Products
Markets
Time dimensions

Developed calculated measures:
Total Revenue
Profit Percentage
Repeat Customer %
Revenue vs Goal comparison

Built slicers for:
Country
Market
Order Year

📈 Key Analysis & Insights
🔹 Market Performance:
APAC:
Highest revenue contribution
Highest profit among all markets

US & EU:
Strong revenue presence
Moderate profit contribution

Canada:
Lowest profit contribution
Indicates possible high operational or logistics costs

LATAM & Africa:
Emerging markets with growth potential but lower profitability

🔹 Customer Behavior Analysis
Repeat customer percentage is evenly distributed across markets
No market exceeds ~16% repeat customers
Indicates customer retention is an improvement opportunity globally

🧠 Key Learnings:
High sales volume does not always translate to high profit
Regional cost structures significantly impact profitability
Customer retention rates are critical for long-term growth
Dashboards are most impactful when KPIs and drill-down insights coexist

📦 What’s Inside This Dashboard:
KPI cards for revenue, profit %, and top product
Bar charts for Revenue by sub-category & segment
Quantity by sub-category
Treemap for market-wise revenue contribution
Line chart showing profit variation across markets
Pie chart for repeat customer analysis
World map for geographical sales distribution
Slicers for interactive exploration

📐 Concepts Applied:
Data Modeling (Star Schema concepts)
KPI & Business Metrics design
DAX calculations & measures
Market segmentation analysis
Customer retention analysis
Time-based trend comparison
Data visualization best practices
Interactive dashboard design

🚀 Future Enhancements:
Add YoY growth % and forecasting
Drill-through pages for market-level deep dives
Product-level profit margin analysis
Customer lifetime value (CLV) calculation
Automated data refresh pipeline
