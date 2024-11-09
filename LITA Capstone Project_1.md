# LITA Capstone Project 1

## Sales Data Analysis Report
### Author: Ozioma
### Date: Tuesday, 5th November, 2024

## OUTLINE
[Exploratory Data Analysis With Excel](#Exploratory-Data-Analysis-With-Excel)

[SQL Data Exploration](#sql-data-exploration)

[ Power BI Report](#power-bi-report)



## CONTENT
## Exploratory Data Analysis With Excel

### Project Overview
This report provides an analysis of sales data with a focus on:
- Total sales by product and region.
- Monthly sales trends.
- Key insights and recommendations based on the analysis.

### Dataset Description
Sales Data: This is an Excel worksheet, it contains 50,001 records with columns for:
- OrderID, 
- CustomerID, 
- Product, 
- Region, 
- OrderDate,
- Quantity, and 
- UnitPrice.

### Analysis Objectives
By the end of this Analysis, I hope to:
- Summarize total sales by product and region.
- Analyze monthly sales trends.
- Calculate metrics like average sales per product and total revenue by region.
- Visualize the top-performing products and monthly sales trends.

### Methodology
To carry out my analysis, Using Microsoft Excel as my analysis tool, I performed the following tasks:
- Data Cleaning: Verified no blank cells, and formatted the columns.
  ![Screenshot (239)](https://github.com/user-attachments/assets/5eb6fcb8-577b-4bf1-b49d-99afda4de45b)
- Data Aggregation: Created calculated columns (Total Sales = Quantity * UnitPrice) and used pivot tables.
  ![Screenshot (229)](https://github.com/user-attachments/assets/f2acaafa-7caf-4188-ace6-ce95d3cddd5b)
  ![Screenshot (237)](https://github.com/user-attachments/assets/7c5ccd81-7fb6-4d04-a50c-230f3e5091f7)
- Visualization: Created bar and line charts for quick insights into product performance and monthly sales trends.
  ![Screenshot (238)](https://github.com/user-attachments/assets/9c1ca6fa-4314-4f77-b581-2706950d36ea)
![Screenshot (236)](https://github.com/user-attachments/assets/d117297f-1fd8-4238-8d06-23f27fb6a3f9)

### Key Findings
- Top-Performing Products: Among the six products—Gloves, Hat, Jackets, Shirt, Shoes, and Socks—Shoes emerged as the top-selling item, with total sales amounting to 3,087,500.
- Revenue by Region: Revenue analysis across four regions—East, North, South, and West—revealed that the South region generated the most revenue, totaling 4,675,000. 
- Monthly Trends: Displayed with a line graph, showing monthly fluctuations in sales; Sales trends across months showed that in 2023, February had the highest sales, with July as a close second. In 2024, February again led with the highest sales, followed closely by January

### Recommendations
- Consider targeting the south regions with additional marketing to increase sales,
- Focus on inventory management for shoes to meet growing demand, and
- Regularly update customer data to maintain accurate subscription insights.

## SQL Data Exploration 

### Overview 
Exploring the data further, I will be using SQL to analyze my sales data. I would first of all Import the sales data into sql, followed by queries that extract meaningful insights. Each section shows a description of the query’s purpose, letting the images tell the story.

![Screenshot (240)~2](https://github.com/user-attachments/assets/50e0e68b-987e-4439-87ee-ef8e19a5748b)



### Data Import
Objective: Import Excel data into SQL Server for analysis.
Using the SQL Server Import and Export Wizard, I initially intended to import the data as an Excel file, I ran into an error related to the 'Microsoft.ACE.OLEDB.12.0' and resolved the error by converting files to CSV format, then successfully imported them.



![Screenshot (241)~2](https://github.com/user-attachments/assets/9e1252a5-ab93-4e3e-b0a5-97a74e23af31)



### Setting Up the Database
Structured the SalesData and CustomerData tables, ensuring columns like OrderID, CustomerID, and Revenue were set up correctly.
Verified data integrity with checks for empty cells and unique identifiers.


## Analysis and Queries

### Total Sales per Product Category
Retrieve the total sales amount for each product category.


![Screenshot (245)~2](https://github.com/user-attachments/assets/bb861492-1cf0-44c8-b10f-27a34701fa41)

This query sums up the sales for each category, helping identify which products generate the most revenue.

### Sales Transactions by Region
Find the number of sales transactions in each region.

![Screenshot (243)~2](https://github.com/user-attachments/assets/bc637c65-5b1a-4f63-a49b-f03cfd32faa5)

Here we can see the transaction count, providing insight into which regions are most active.

### Highest-Selling Product by Sales Value
Identify the product with the highest total sales value.

![Screenshot (244)~2](https://github.com/user-attachments/assets/2c5e8b6d-775c-4f93-bbfe-ae061616a136)

This query pinpoints the top-performing product by calculating the total sales value.

### Total Revenue by Product
Calculate the total revenue for each product.

![Screenshot (246)~2](https://github.com/user-attachments/assets/6543ea11-846b-4049-868c-3c4f87f4aefd)

Shows the revenue contribution of each product individually.

### Monthly Sales Totals for the Current Year
Summarize total sales for each month in the current year.

![Screenshot (247)~2](https://github.com/user-attachments/assets/fa8fc839-b441-42f8-9528-8772bccc148f)

Tracking monthly sales trends, allowing us to identify seasonal patterns.

### Top 5 Customers by Purchase Amount
Determine the top 5 customers based on total purchases.

![Screenshot (248)~2](https://github.com/user-attachments/assets/d5a1ef12-cd10-43f5-9f77-f951dc831f29)

Highlighting the customers with the highest purchases is useful for loyalty and targeted marketing.

### Regional Sales Contribution Percentage
Calculate the percentage of total sales contributed by each region.

![Screenshot (249)~2](https://github.com/user-attachments/assets/6dfa68b0-feec-4734-bd17-de95fd411f93)

Reveals which regions contribute the most to overall sales, Here we can see that the south generates the most revenue, by contributing to 44% of the total revenue.

### Products with No Sales in the Last Quarter
Identify products with no sales in the most recent quarter.

![Screenshot (250)~2](https://github.com/user-attachments/assets/0c7678ba-8c2f-4bcd-b341-9bd34eb9fa2b)

Highlights products with Sales in the last quarter of July and August as Shoe, Hat, and Shirts, Revealing that Jackets, Socks, and Gloves had no sales, which is useful for inventory decisions.

Conclusion
This analysis provides a high-level view of sales patterns, top products, key customers, and regional contributions. These insights can guide decisions around marketing, inventory, and regional focus.



## Power BI Report
### Project Overview
Using Microsoft Power BI, I will now analyze the sales data to identify top-performing products, regional performance, and monthly trends for a retail store.

### Data Source
Sales data was imported into Power BI, with previous data exploration performed in Excel and SQL.

### Data Preparation
Loaded Datasets: Connected Power BI to two datasets:
Sales Data: Includes columns like OrderID, CustomerID, Product, Region, OrderDate, Quantity, and UnitPrice.

![Screenshot (253)](https://github.com/user-attachments/assets/87a312aa-022a-4df5-b089-5679b213f707)


### Data Transformations
Created a calculated column for Total Sales by multiplying Quantity and UnitPrice.
Added a Year column using DAX (Year = YEAR(SalesData[OrderDate])) to simplify yearly filtering.

![Screenshot (256)](https://github.com/user-attachments/assets/6ffdba9e-b4c3-47b2-b524-7441d740bfc9)


### Dashboard Design

#### Sales Overview:

Total Sales: Displayed as a KPI card showing total sales across all periods.

Sales Trend by Month: Line chart to visualize monthly sales fluctuations, filtered by year.

![Screenshot (266)](https://github.com/user-attachments/assets/3a50166c-388a-4077-8669-e09312e110f0)


![Screenshot (267)](https://github.com/user-attachments/assets/c09cf31a-3c63-4863-9603-ec99daadcc00)


![Screenshot (268)](https://github.com/user-attachments/assets/23402886-d863-4c92-8658-caa32a2abab9)


#### Top-Performing Products:

Top Products by Sales: Bar chart showing sales for each product, with Shoes as the highest performer.

Product Contribution to Total Sales: The donut chart shows the percentage of contribution to each product category.

![Screenshot (263)](https://github.com/user-attachments/assets/24c1640c-2f0b-4e7e-9d1f-dac39253a51c)


#### Regional Breakdown:

Sales by Region: The bar chart shows sales per region, with South as the top revenue-generating region.

Revenue by Region: Pie chart displaying each region’s percentage contribution.

![Screenshot (262)](https://github.com/user-attachments/assets/66c74bb6-1285-4a3f-8f38-4f0d3d460f2e)


### Interactive Features
Year Slicer: Slicer for Year with options for 2023 and 2024, allowing users to filter and compare sales trends across years.
Product and Region Filters: Filters added to allow selection of specific products or regions for detailed analysis.


### Key Insights
Top-Performing Product: Shoes generated the highest sales, totaling $3,087,500.
Top Revenue-Generating Region: The South region contributed the highest revenue of $4,675,000.
Monthly Sales Trends:
2023: February had the highest sales, with July as a close second.
2024: February and January were the top months.

### Conclusion
Using the three data analysis tools, I was able to analyze, Query and Display insights from my Sales data, Demonstrating the reliability and usefulness of this tools in Data Analysis.


### IN PROGRESS NATIONAL GRID HAS AFFECTED GREATLY 
