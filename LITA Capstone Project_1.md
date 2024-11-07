# LITA Capstone Project 1

## Sales Data Analysis Report
### Author: Ozioma
### Date: Tuesday, 5th November, 2024

[SQL Data Exploration](#sql-data-exploration)

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
This report presents a SQL-based analysis of sales and customer data. It includes setup steps for data import, followed by queries that extract meaningful insights. Each section shows a description of the query’s purpose, letting the images tell the story.



### Data Import
Objective: Import Excel data into SQL Server for analysis.
Using the SQL Server Import and Export Wizard, I initially intended to import the data as an Excel file, I ran into an error related to the 'Microsoft.ACE.OLEDB.12.0' and resolved the error by converting files to CSV format, then successfully imported them.

### Setting Up the Database
Structured the SalesData and CustomerData tables, ensuring columns like OrderID, CustomerID, and Revenue were set up correctly.
Verified data integrity with checks for empty cells and unique identifiers.

Analysis and Queries

### Total Sales per Product Category
Objective: Retrieve the total sales amount for each product category.

Description: This query sums up the sales for each category, helping to identify which products are generating the most revenue.

### Sales Transactions by Region
Objective: Find the number of sales transactions in each region.

Description: Displays the count of transactions, providing insight into which regions are most active.

### Highest-Selling Product by Sales Value
Objective: Identify the product with the highest total sales value.

Description: By calculating total sales value, this query pinpoints the top-performing product.

### Total Revenue by Product
Objective: Calculate total revenue for each product.

Description: Shows the revenue contribution of each product individually.

### Monthly Sales Totals for the Current Year
Objective: Summarize total sales for each month in the current year.

Description: Tracks monthly sales trends, allowing us to identify seasonal patterns.

### Top 5 Customers by Purchase Amount
Objective: Determine the top 5 customers based on total purchases.

Description: Highlights the customers with the highest purchases, useful for loyalty and targeted marketing.

### Regional Sales Contribution Percentage
Objective: Calculate the percentage of total sales contributed by each region.

Description: Reveals which regions contribute the most to overall sales.
### Products with No Sales in the Last Quarter
Objective: Identify products with no sales in the most recent quarter.
Description: Highlights products with declining or no sales, useful for inventory decisions.
Conclusion
This analysis provides a high-level view of sales patterns, top products, key customers, and regional contributions. These insights can guide decisions around marketing, inventory, and regional focus.

Let me know if you'd like to add or adjust any descriptions! This layout keeps it straightforward, with the images and brief descriptions leading the way.







### IN PROGRESS NATIONAL GRID HAS AFFECTED GREATLY 
