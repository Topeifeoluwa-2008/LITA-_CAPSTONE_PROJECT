# LITA_CAPSTONE_PROJECT
## Project 1 Title: Sales Performance Analysis for a Retail Store

### Introduction
Analyzing sales performance is crucial for any retail store looking to improve its profitability, optimize product offerings, and enhance customer satisfaction. This project focuses on conducting an in-depth analysis of a retail store's sales data to uncover insights related to top-selling products, regional sales performance, and monthly sales trends. The goal is to develop a comprehensive Power BI dashboard that integrates findings from Excel and SQL analyses, providing an interactive overview for stakeholders to make data-driven decisions.

### Problem Statement
The retail industry is highly competitive, with businesses striving to understand their sales patterns to maintain a competitive edge. This project aims to address the following business questions:
Which products are the top sellers?
How does sales performance vary by region?
What are the monthly sales trends?
Who are the most valuable customers by purchase volume?
Which products have not performed well in the last quarter?

### Data Sources
Data Sourcing
The dataset used in this analysis is derived from internal sales records of the retail store, provided in an Excel file format. 
-   The dataset includes fields such as:
-   Product names and categories,
-   Transaction dates and details,
-   Revenue and sales quantities,
-   Customer data and regional sales information,
This data was loaded into Excel for initial exploration and into a SQL Server environment for deeper querying and analysis.

### Tools Used
- Microsoft Excel
   i. Data Cleaning
  ii. Analysis
iii. Visualization

- SQL - Structured Query Language for Query of Data
- Power Bi for data analysis and visualisation
- Github for Portfolio Building

### Data Cleaning and Preparation
In the initial phase of the data cleaning and preparations, we perform the following action
* Data loading and Inspection
* Handling mission variables
* Data cleaning formatting

### Exploratory Data Analysis
EDA involves the exploring of the Data to answer some question about the Data such as;
What is the overall sales trend
Which product are top sellers
What are the Products on peak sales?

Data Transformation
The data transformation process involved:

Excel Exploration:
Summarizing sales data using pivot tables to show total sales by product, region, and month.
Using Excel formulas to compute average sales per product and total revenue by region.
Generating visual and summary reports to identify high-level trends.


![PIVOTTABLE FOR SALE DATA](https://github.com/user-attachments/assets/0f1a000b-e792-4fa2-8678-3e0eee4e274f)


```SQL
select * from [dbo].[LITA Capstone Dataset]
Importing the dataset into SQL Server for querying.
Writing SQL queries to extract and calculate key performance metrics, such as total revenue per product, top-performing products, and monthly sales totals.
Using SQL functions to identify products without sales in the last quarter and calculate the percentage of total sales contributed by each region.

### Analysis and Key Insights
*  Excel Analysis:
*  Initial analysis revealed the top products by total sales and regions contributing the most to revenue.
*  Average sales per product helped identify best-sellers and underperforming items.
*  SQL Analysis: Querying confirmed the top-selling product categories and highlighted regions with the highest number of sales transactions.
*  Monthly sales totals indicated patterns of seasonality, revealing peak and low sales periods.
*  Customer analysis showed the top 5 customers with the highest purchase amounts, indicating loyal and high-value customers.
*  Products with no recent sales were identified to inform inventory management.
*  Power BI Dashboard: A Power BI dashboard was developed to visualize:

### Sales Overview: A summary of total revenue, average sales, and sales growth over time.
-   Top-Performing Products: A chart showing the top products by sales and revenue.
-   Regional Breakdown: Visuals displaying sales contributions by region.
-   Customer Insights: A section highlighting key customers and their purchase values.

### Recommendations
-   Based on the insights, the following recommendations are suggested:
-   Focus marketing efforts on regions with higher revenue potential and introduce promotions in underperforming regions.
-   Adjust inventory to prioritize top-selling products while reevaluating stock for products with declining sales.
-   Enhance loyalty programs for high-value customers to encourage repeat purchases.
-   Address seasonal sales trends by preparing targeted sales campaigns for peak seasons.

### Conclusion
The analysis provided a comprehensive view of the retail store's sales performance, highlighting key products, customers, and regions. By implementing the recommendations and leveraging the interactive Power BI dashboard, the retail store can make informed strategic decisions to improve profitability and enhance customer engagement.


