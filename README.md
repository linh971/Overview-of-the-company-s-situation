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
#### 2.2.1. Information Value - Categorical Variables
### 2.3. Data Visualisation
#### 2.3.1. Business and operational situation
<img src="https://imgur.com/a/QX4UYsn">

