# LITA Capstone Project 2

## Customer Subscription Analysis Report
## Author: Ozioma Orji

### Overview
This report analyzes customer subscription data across different regions, subscription types, statuses, and revenue contributions. The goal is to understand key trends and insights that could guide strategic decisions for customer engagement, retention, and revenue optimization.

### Outline 

[Microsoft Excel Data analysis]( Microsoft-Excel-Data-analysis)

[SQL DATA EXPLORATION](SQL-DATA-EXPLORATION)

[POWER BI DATA VISUALIZATION](POWER-BI-DATA-VISUALIZATION)
 
### Data Summary
The dataset consists of 75,001 rows of customer data with columns for:

Region: Geographical location of customers (North, East, South, West)

Subscription Type: Different subscription plans (Basic, Premium, Standard)

Subscription Status: Whether a subscription is active or canceled

CustomerId: Unique identity for the customers 

Customer name: The name of the customer 

Subscription start date: The beginning of a purchase subscription 

Subscription Emd date: The expiry date of a subscription 

![Screenshot (273)](https://github.com/user-attachments/assets/ec89bcde-143a-4577-860b-9c3067474c11)


## Microsoft Excel Data analysis

Using Microsoft Excel, I ensured the data was properly validated, checking for data types and null values. Then, to carry out my analysis, I created pivot tables that summarised the data, enabling me to acquire insights into my customer data. These insights were then visualized to communicate the insights with charts.

### Data Analysis and Visualizations

### Regional Performance 
Purpose: To understand the distribution of subscription types across regions.

#### Findings:

North and East: Predominantly have customers on the Basic subscription.
South: Has a higher number of Premium subscriptions.

West: Mainly has Standard subscriptions.

#### Visualization:
A pivot table showing customer counts by region and subscription type, with a corresponding bar chart.

### Subscription Summary 
Purpose: To assess the activity levels of different subscription types.

#### Findings:
Basic subscriptions have the largest share, with a significant portion being active, indicating high retention.
Other subscription types (Premium and Standard) show a balance between active and canceled statuses, but the active count for Basic subscriptions stands out.

#### Visualization:
A pivot table with subscription types and their status, accompanied by a stacked column chart for active vs. canceled proportions.

### Revenue Generated 
Purpose: To analyze revenue contributions from each region.

#### Findings:

The South region has the highest revenue, although the difference is marginal across regions, as shown by both the pie and bar charts.
A zero-based bar chart and pie chart reveal that revenue contributions are relatively balanced across regions.

#### Visualization:
A pivot table summarizing revenue by region, supported by both pie and bar charts to emphasize the equal distribution.

![Screenshot (270)](https://github.com/user-attachments/assets/c49641f7-9491-4375-92a3-1f5257dbc0fc)


![Screenshot (272)](https://github.com/user-attachments/assets/311c3cc0-0a37-47a6-b7ab-255430c966f8)


### Key Insights
Basic Subscription Dominance: Basic subscriptions lead in customer count and active status, making it a key focus area for retention and engagement.

Balanced Revenue Distribution: Revenue across regions shows only slight variations, suggesting that growth strategies should target all regions equally rather than focusing on specific ones.

Regional Preferences: Subscription preferences vary by region, with the South favoring Premium and the West opting for Standard, which may guide targeted marketing efforts.

## SQL DATA EXPLORATION 
Using SQL for data exploration, I ran queries on my customer data to acquire key insights into customer subscription patterns, cancellations, and revenue generation.
![Screenshot (275)](https://github.com/user-attachments/assets/4b007441-e31c-488f-a809-168e2a0ae078)


### Data Exploration 

#### Total Number of Customers by RegionResult:
![Screenshot (277)](https://github.com/user-attachments/assets/a8eef3ed-8ac6-4d73-8df4-69472d3e6f94)


Result: Each region has an equal number of customers.

#### Most Popular Subscription TypeResult:
![Screenshot (278)](https://github.com/user-attachments/assets/a63189c6-7345-4788-9068-8fc47d54fa93)


Result: The basic subscription type has the most customers.

#### Query: Customers Who Canceled Their Subscription Within 6 Months

![Screenshot (279)](https://github.com/user-attachments/assets/964ddcce-5b36-455b-a655-a990d070c36e)

Result: No customer canceled their subscription within 6 months. 

#### Average Subscription Duration 

![Screenshot (280)](https://github.com/user-attachments/assets/da4e2fc1-d8df-445e-b0a4-9bf544c8e30f)

Result: The average subscription duration is 365 days.

#### Customers with Subscriptions Longer Than 12 Months

![Screenshot (281)](https://github.com/user-attachments/assets/142a94bf-8455-40e5-abfc-d9dbee653717)

Result: No customer has a subscription longer than 12 months.

#### Total Revenue by Subscription Type 

![Screenshot (282)](https://github.com/user-attachments/assets/0432baf9-da9b-49e4-a1d8-10673f9c4613)

Result: Basic subscriptions generate the most revenue due to the highest number of customers.

#### Top 3 Regions by Subscription Cancellations

![Screenshot (284)](https://github.com/user-attachments/assets/22860f23-d729-4393-8486-c4590d2033e5)

Result: North, South, and West have equal numbers of canceled subscriptions, while East has none.

#### Total Active and Canceled Subscriptions 

![Screenshot (285)](https://github.com/user-attachments/assets/385822ba-36a2-4678-8317-28f6ec4659c3)

Result: There are more active subscriptions than canceled subscriptions.

### Summary
This analysis shows:
Customer Distribution: Equal number of customers across regions.

Subscription Preferences: Basic subscription is the most popular and highest revenue-generating type.

Subscription Duration: The average subscription lasts 365 days, with no subscriptions less than 6 months or longer than 12 months.

Cancellations: North, South, and West have the same cancellation rates, while East has none.

## POWER BI DATA VISUALIZATION

In this session, using Power BI, I visualized the customer data analysis insight to show behavior patterns, track subscription types, and uncovering trends in cancellations and renewals. The report is presented through a Power BI dashboard, segmented into three main pages for clear insight.

### Customer Overview
Objective: Provide a summary of customer activity and transaction distribution.

Visualizations:
The Total Transactions Card displays the total number of transactions recorded (e.g., 75,000). The Customer Count Card shows the number of unique customers contributing to these transactions.
Customer Details Table: Lists customer names, their regions, and the number of transactions.
Slicer: Filters the visualizations based on Subscription Status (Active or Canceled).

![Screenshot (297)](https://github.com/user-attachments/assets/39c2bf49-c444-4997-b654-b946d48abab2)

### Subscription Summary
Objective: Highlight subscription patterns and revenue, giving a detailed view of types and status.

Visualizations:
Subscription Type Pie Chart: This chart displays the distribution of all subscription types by customer count (Basic, Premium, Standard, etc.).
Subscription Status Pie Chart: This shows the proportion of active and canceled subscriptions.
Revenue Card: Total revenue generated from all subscriptions.
Average Subscription Duration Card: Average duration of subscriptions across all customers.Transaction Count: The total number of transactions recorded.
Dynamic Filtering: Interactions across visualizations allow for deep insights by filtering each visual based on selections made within the page.

![Screenshot (296)](https://github.com/user-attachments/assets/b5f4406c-3feb-4dca-b3f9-59d3e035e1e6)

### Regional Performance
Objective: Analyze performance metrics across different regions.

Visualizations:
Number of Regions Card: Total number of regions represented.Customer Count: Number of customers across all regions.
Revenue Generated Card: Total revenue attributed to each region.
Regional Details Table: Lists each region along with its customers and transaction count for detailed insights.
Revenue by Region Pie Chart: Shows the revenue distribution across regions, revealing that the South has the highest revenue, albeit by a slight margin.
Subscription Type Slicer: Filters regional data by specific subscription types, allowing analysis of each type’s performance by region.

![Screenshot (295)](https://github.com/user-attachments/assets/94c55c17-b925-49fa-b2f7-60b80ecb094e)

Conclusion
The Power BI dashboard provides a comprehensive view of customer segmentation, highlighting subscription trends, revenue, and regional performance. Key insights, like the dominance of the Basic subscription type and the slightly higher revenue generated by the South region, provide actionable insights for business strategies.
