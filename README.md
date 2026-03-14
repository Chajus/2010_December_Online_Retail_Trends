# 2010_December_Online_Retail_Trends

**Online Retail Sales Analysis – December 2010
Project Overview**
- This project analyzes an online retail dataset to identify sales trends, top-performing products, and high-value customers during December 2010. The goal of this project was to practice data cleaning, data analysis using SQL, and data visualization using Tableau.
- The dataset contains transactional retail data including product information, quantities purchased, unit prices, and customer IDs.

**Objectives**

- The analysis focuses on answering the following business questions:
- What was the total revenue generated in December 2010?
- Which products generated the most revenue?
- Which customers spent the most money?
- How did revenue change on a daily basis?

**Tools Used**

**SQL**
- Data exploration
- Revenue calculations
- Identifying top customers and products

**Tableau**
- Data visualization
- Dashboard creation
- Trend analysis

**Dataset**
- Dataset: Online Retail Dataset
- The dataset contains transactional records with the following relevant fields:
- InvoiceNo – unique order identifier
- StockCode – product ID
- Description – product name
- Quantity – number of items purchased
- InvoiceDate – transaction timestamp
- UnitPrice – price per unit
- CustomerID – unique customer identifier

**Data Preparation**
- The following steps were performed during data cleaning and preparation:
- Removed or ignored returned items where Quantity was less than or equal to zero
- Calculated revenue using the formula:
- Revenue = Quantity × UnitPrice
- Converted timestamps into daily dates for time series analysis
- Exported cleaned data into CSV format for visualization

**Tableau Dashboard**

- The Tableau dashboard visualizes the results of the analysis.
- It includes the following visualizations:
- Top 10 Products by Revenue
- Displays the products generating the highest revenue.
- Top 10 Customers by Spending
- Identifies the highest value customers.
- Daily Revenue Trend
- Shows how revenue fluctuated throughout December 2010.

**Key Insights**

- Revenue fluctuated significantly during December, with several spikes indicating higher purchasing activity on certain days.
- A small number of products generated a large portion of total revenue, highlighting the importance of top-performing items.
- Customer spending was highly concentrated, with a few customers accounting for significantly higher purchases than others.
