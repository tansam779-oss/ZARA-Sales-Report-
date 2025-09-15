# ZARA-Sales-Report
**Short Description / Purpose**  
Power BI project analyzing ZARA’s sales dataset from Kaggle. The data was cleaned, modeled, and visualized to explore customer purchasing patterns, product performance, and the impact of promotions. The dashboard tracks KPIs such as sales volume, revenue, and promotional activity. 

**Tech Stack**  
- Power BI Desktop — visuals and DAX measures  
- Power Query / PowerPivot — data cleaning and reshaping  
- Excel — data staging from Kaggle CSVs  
- DAX (Data Analysis Expressions) — KPIs and aggregations  
- Data Modeling — fact tables with dimensions (product, section, promotion, price range)  

**Data Source**  
- Kaggle 
- Dataset includes product ID, product name, category, section, price, sales volume, sales date, and promotion status.  
---
**Features / Highlights**  
- KPI cards for total sales volume, products on promotion, non-promotional products, and total revenue  
- Sales volume by price range distribution  
- Sales volume by section (Men vs. Women)  
- Sales volume by promotion (Yes/No)  
- Bubble chart showing sales volume and revenue by price, segmented by section  
- Date-specific snapshot: report built for February 19, 2024  

## Business Problem
- ZARA operates with a wide product mix across Men’s and Women’s sections.  
- Management needs visibility on sales performance by section, promotion, and price range.  
- It is essential to understand which price ranges drive the highest sales.  
- Promotional impact must be measured to decide on future campaigns.  
- Without consolidated insights, inventory and marketing strategies may be misaligned.  
## Stakeholders
- ZARA retail management — requires insights into sales distribution.  
- Marketing team — evaluates the effectiveness of promotions.  
- Merchandising team — identifies which price points and categories perform best.  
- Data analytics team — responsible for data transformation and maintaining reports.  
## Goal of the Dashboard
- Provide a one-page interactive dashboard to track ZARA’s sales KPIs.  
- Compare promotional versus non-promotional product sales.  
- Analyze sales volume distribution across price ranges.  
- Segment insights by section (Men/Women) for targeted strategy.  
- Deliver revenue and sales patterns in an executive-friendly format.  
## Walkthrough of Key Visuals
- Total Sales Volume, Products on Promotion, Non-Promotional Products, and Total Revenue KPIs  
- Bar chart: Sales Volume by Price Range  
- Bar chart: Sales Volume by Section  
- Bar chart: Sales Volume by Promotion  
- Bubble chart: Sales Volume and Revenue by Price, segmented by section  

## Business Impact & Insights
- Reveals which price ranges generate the most sales volume.  
- Shows that Men’s section contributed significantly more sales than Women’s section on the selected date.  
- Highlights revenue impact from promotions versus non-promotions.  
- Enables data-driven decisions for marketing campaigns and inventory planning.  
## Screenshots / Demos
Dashboard preview (February 19, 2024):  

![Dashboard Preview](Zara%20Sales%2019Feb%202024.png)  
## Problem Statements
- What is the total sales volume and revenue for ZARA?  
- How do promotions affect product sales?  
- Which section (Men/Women) contributes more to sales?  
- Which price ranges drive the highest sales volumes and revenues?  
- How can promotions be optimized to maximize revenue?  
## Approach - Project Planning & Aims Grid
1. Purpose  
Transform raw Kaggle dataset into a Power BI dashboard to analyze ZARA’s sales performance by section, promotion, and price range.  
2. Stakeholders  
Retail managers, marketing teams, merchandising planners, and analytics teams who rely on accurate sales insights.  
3. End Result  
An interactive dashboard with validated KPIs that shows sales volumes, revenue, promotional effectiveness, and product section performance.  

4. Success Criteria  
Accurate aggregation of sales data, correct segmentation by price range, clear distinction between promotional and non-promotional sales, and intuitive visuals for decision-makers.  

## Data Analysis – Approach
- Download dataset from Kaggle.  
- Stage and clean data in Excel, reshape with Power Query.  
- Build fact tables (sales) and dimension tables (product, section, promotion, price range).  
- Create DAX measures for total sales volume, revenue, products on promotion, and non-promotional products.  
- Design visuals: KPIs, bar charts, bubble chart, and segment filters.
- Validate totals against source dataset and deliver an interactive dashboard for business use.  

--
**Disclaimer**  
This project is created solely for educational and demonstration purposes. It is not affiliated with or endorsed by ZARA or Inditex. The data used in this dashboard is sourced from Kaggle’s publicly available dataset. No confidential or proprietary information is included. Users should not rely on this project for financial decision-making or business forecasting.  
