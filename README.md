# Sales Overall Business Intelligence Dashboard

## Project Overview and Purpose
This project is a comprehensive Business Intelligence solution developed in Power BI to analyze global sales performance. The dashboard transforms raw transactional data into interactive visual insights, allowing stakeholders to track revenue growth, identify top-performing products, and monitor regional sales distribution in real-time.

## Key Features and Visualizations
- **Executive Summary**: High-level KPIs including Total Revenue, Profit Margin, and Total Units Sold.
- **Sales Trends**: Time-series analysis (Monthly/Quarterly) to identify seasonal peaks and year-over-year growth.
- **Geographic Insights**: Interactive maps showing sales distribution across different countries and regions.
- **Product Performance**: Breakdown of sales by category and sub-category to identify "Best Sellers" and "Underperformers."
- **Customer Segmentation**: Analysis of sales across different customer types (Consumer, Corporate, Home Office).



## Technologies Used
- **Power BI Desktop**: For data modeling, DAX calculations, and report design.
- **Power Query (M Language)**: For ETL (Extract, Transform, Load) processes and data cleaning.
- **DAX (Data Analysis Expressions)**: Created custom measures for profit ratios, year-to-date (YTD) sales, and growth percentages.

## Data Structure
The dashboard is built upon a relational data model (Star Schema) consisting of:
- **Fact Table**: Sales Transactions (Orders).
- **Dimension Tables**: Calendar/Date, Products, Customers, and Geography.

## How to View the Project
1. **Software**: You will need [Power BI Desktop](https://powerbi.microsoft.com/desktop/) installed to open the file.
2. **Opening the Report**: Download and open the `Sales Overall.pbix` file.
3. **Interactivity**: Use the slicers on the side or top of the report to filter data by year, region, or product category.
