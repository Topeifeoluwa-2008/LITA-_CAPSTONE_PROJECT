# LITA_CAPSTONE_PROJECT
## Project 1 
## Title: Sales Performance Analysis for a Retail Store

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

![EXCEL CHART SALESDATA](https://github.com/user-attachments/assets/f42841ec-02ec-4f20-8f9a-cc13fbf3d19d)


-   SQL

Importing the dataset into SQL Server for querying.
Writing SQL queries to extract and calculate key performance metrics, such as total revenue per product, top-performing products, and monthly sales totals.
Using SQL functions to identify products without sales in the last quarter and calculate the percentage of total sales contributed by each region.

![SQL PROJECT 1](https://github.com/user-attachments/assets/797c823a-bba4-4453-b06b-44bdb8222b01)




### Analysis and Key Insights
*  Excel Analysis:
*  Initial analysis revealed the top products by total sales and regions contributing the most to revenue.
*  Average sales per product helped identify best-sellers and underperforming items.
*  SQL Analysis: Querying confirmed the top-selling product categories and highlighted regions with the highest number of sales transactions.
*  Monthly sales totals indicated patterns of seasonality, revealing peak and low sales periods.
*  Customer analysis showed the top 5 customers with the highest purchase amounts, indicating loyal and high-value customers.
*  Products with no recent sales were identified to inform inventory management.
*  Power BI Dashboard: A Power BI dashboard was developed to visualize:


![Sales data report PowerBi](https://github.com/user-attachments/assets/edfc6c29-8069-4211-b4f8-3d28cc843808)

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




project 2

## Customer Segmentation for a Subscription Service

Introduction
Customer segmentation is a powerful analytical approach used by subscription services to understand and respond to customer behaviors, preferences, and trends. By segmenting customers, companies can tailor their offerings, improve customer retention, and increase revenue. This project focuses on analyzing customer data to identify subscription patterns, track the most popular and long-term subscriptions, and understand trends in cancellations and renewals. The final output is an interactive Power BI dashboard that effectively presents these findings.

## Problem Statement
Subscription services often face challenges related to customer churn, identifying valuable customer segments, and understanding key drivers behind subscription renewals and cancellations. This project aims to address the following questions:
-   Which subscription types are most popular?
-   What is the average subscription duration?
-   Which customers have subscriptions longer than 12 months?
-   Which regions have the highest number of cancellations?
-   What trends are observed in active vs. canceled subscriptions?

## Data Sourcing
The customer data for this analysis was sourced from internal subscription service records and was provided in an Excel format. 
The dataset includes:
*   Customer demographics and regional information
*   Subscription start and end dates
*   Subscription types and associated revenue
*   Status of subscriptions (active or canceled)
* 
This data was utilized in Excel for initial exploration and in SQL for detailed querying and analysis.

Data Transformation
The data transformation process involved the following steps:

Excel Analysis:
*   Creating pivot tables to analyze customer data and identify trends in subscription patterns by type and region.
*   Calculating the average subscription duration using Excel formulas.
*   Generating additional reports, such as total revenue per subscription type and cancellation trends.
  
![Customer Report Pivot Table](https://github.com/user-attachments/assets/38cd9d9b-671e-48df-9704-cc38bce7d1da)

![CHART FOR CUSTOMERDATA](https://github.com/user-attachments/assets/b5f23516-226d-4567-8c06-4763f73b2848)


## SQL Analysis:
*   Loading the dataset into SQL Server for deeper analysis.
*   Writing SQL queries to answer key business questions:
*   Total number of customers by region.
*   Most popular subscription types based on customer count.
*   Identification of customers who canceled within 6 months of starting their subscription.
*   Calculation of average subscription duration and identification of long-term subscribers (over 12 months).
*   Total revenue breakdown by subscription type.
*   The top 3 regions with the highest subscription cancellations.
*   Count of active and canceled subscriptions.

![SQL PROJECT 2](https://github.com/user-attachments/assets/4ff36bff-6788-427f-adb9-f4570bcf2893)

Analysis and Key Insights
Excel Analysis:
The analysis revealed that specific subscription types are more popular than others, helping to inform marketing and product strategies.
The average subscription duration provided insights into customer loyalty and lifecycle.
SQL Analysis:
The most popular subscription type was identified through the customer count.
Customers who canceled their subscription within the first 6 months were highlighted, revealing potential issues in the early subscription phase.
The SQL queries also calculated total revenue per subscription type, emphasizing high-value and less profitable subscriptions.
The regions with the highest cancellation rates were identified to inform targeted retention strategies.

## Power BI Dashboard
- The Power BI dashboard was designed to present key findings interactively:
-   Customer Segmentation Overview: A summary highlighting the total number of customers, popular subscription types, and regional distribution.
-   Cancellation Analysis: Visuals showing the number of cancellations over time, with slicers to filter by region and subscription type.
-   Subscription Duration Insights: Charts depicting average duration and the number of long-term subscribers.
-   Revenue by Subscription Type: A breakdown showing which subscription types generate the most revenue.

  ![Customer Report Power Bi](https://github.com/user-attachments/assets/4d259405-2449-4119-bc00-c3033515d6e5)

## Recommendations
Based on the analysis, the following recommendations are proposed:
-   Enhance customer onboarding for new subscribers to reduce early cancellations.
-   Implement targeted retention efforts in regions with the highest cancellation rates.
-   Focus on promoting the most popular and profitable subscription types.
-   Offer incentives or loyalty programs for long-term subscribers to maintain and improve customer retention.

## Conclusion
This customer segmentation project provided valuable insights into the subscription service's customer base, subscription patterns, and cancellation trends.
The Power BI dashboard enables stakeholders to explore the data interactively, aiding in strategic decisions that can improve retention and revenue.
By leveraging these findings, the company can enhance its subscription offerings and strengthen customer relationships.






