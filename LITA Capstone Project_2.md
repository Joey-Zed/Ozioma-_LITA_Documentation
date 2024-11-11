# LITA Capstone Project 2

## Customer Subscription Analysis Report
## Author: Ozioma Orji

### Overview
This report analyzes customer subscription data across different regions, subscription types, statuses, and revenue contributions. The goal is to understand key trends and insights that could guide strategic decisions for customer engagement, retention, and revenue optimization.

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
Using sql for data exploration,I ran queties on my customer data to acquire key insights into customer subscription patterns, cancellations, and revenue generation.

### Data Exploration 

#### Total Number of Customers by RegionResult:


Result: Each region has an equal number of customers.

#### Most Popular Subscription TypeResult:


Result: Basic subscription type has the most customers.

#### Query: Customers Who Canceled Their Subscription Within 6 Months


Result:No customer canceled their subscription within 6 months. 

#### Average Subscription Duration 


Result:The average subscription duration is 365 days.

#### Customers with Subscriptions Longer Than 12 Months


Result: No customer has a subscription longer than 12 months.

#### Total Revenue by Subscription Type 


Result:Basic subscriptions generate the most revenue due to the highest number of customers.

#### Top 3 Regions by Subscription Cancellations


Result: North, South, and West have equal numbers of canceled subscriptions, while East has none.

#### Total Active and Canceled Subscriptions 


Result: There are more active subscriptions than canceled subscriptions.

### Summary
This analysis shows:
Customer Distribution: Equal number of customers across regions.

Subscription Preferences: Basic subscription is the most popular and highest revenue-generating type.

Subscription Duration: Average subscription lasts 365 days, with no subscriptions less than 6 months or longer than 12 months.

Cancellations: North, South, and West have the same cancellation rates, while East has none.

