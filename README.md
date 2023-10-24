# Overview of the company situation
## 1. Introduction
### 1.1. Background
You are a Data Analyst working for an e-commerce company called X. You are tasked with preparing a presentation to present an overview of the company's business and operations up to the present time. for Sales Director and Operations Director. The presentation must at least include the following information: business overview, customer satisfaction level, and suggest 2 to 3 areas (areas) where the company can improve.
### 1.2. Objectives
- Overview of business situation
- Customer satisfaction level
- Suggest 2 to 3 areas (areas) that the company can improve
### 1.3. Methodology &  Tools
- Python: data cleaning, data extraction
- Power BI: data visualisation
- Excel: statistics
- Sql: recalculate data
## 2. Analysis
### 2.1. Data Cleaning
- In this step, I use Python to delete data after September 30, 2018 based on the column "Date Order Purchase Timestamp" in the table "orders_dataset"
- Use Power to separate the date and time columns in the Orders_dataset and review_dataset tables. Create an additional column "Delivery_vs_estimated" in the "Orders_dataset" table to determine the gap between the time the Customer receives the goods and the system's expected delivery time.
- Use SQL to group orders in the "Order_items_dataset" table to determine order value, shipping fee and number of products in 1 order. Left join tables “Orders_dataset” and “Order_items_dataset” to get data before October 1, 2018
### 2.2. Statistics
Here, I will conduct a statistical test to see whether the variables qualify for analysis or not. Use methods to group information
### 2.3. Data Visualisation
#### 2.3.1. Business and operational situation
Overall, the company's business situation is quite good
- Most of the company's customers are in South America and North America
- From 2016 to 2018, there was quite stable growth, rapid growth in 2016-2017, and from 2017-2018 there was growth but not too impressive.
- Order value and delivery rate by year is quite impressive
- Total revenue paid by credit card is the most, followed by cash, vouchers, and debit cards
- Most delivery times are 6-16 days
- Order value and delivery speed over time have also improved significantly from 2017-2018.
#### 2.3.2. Customer satisfaction level
- Most review time frames are under 1 month (98,783 orders), from 2-3 months are 457 orders, 3-6 months are 129 orders, 6-12 are 62 orders
- The number of customers rating 5/5 accounts for 57.37%; 4/5 is 19.22%; 3/5 is 8.3%; 2/5 is 3.24%; 1/5 is 11.8%
- The number of orders, the number of reviews, and the number of reviews are quite uniform.
- Early order status accounts for 89.72%; late is 6.62%
- The number of customers paying in installments and the number of customers paying in one time are almost equal
- Customers who pay in one go pay by credit card, customers who pay in installments with orders from 0-2.5M pay by cash; from 2.5-5.5M credit card
### 2.4. Proposed Solutions
- Customers are concentrated in South America => Need to expand sales areas such as North America and Europe
- The number of orders in September decreased significantly compared to previous months and the same period of the year, with only 16 orders in the entire month of September (the system may not have been updated).
- Shipping fee revenue accounts for nearly 15% of total revenue => Reduce shipping prices to attract customers, to expand areas and customer files.
- Revenue mainly comes from customers using credit cards and customers who tend to pay in installments => Increase incentives for customers who pay in cash to ensure the cash fund is collected.
- Need to increase the average review score of the system and let customers leave comments when reviewing => Create monthly incentive events, minigames to increase interaction. Add member points, exchange gifts, exchange payments.
