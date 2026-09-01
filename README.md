#Velocity Bikes — SQL Sales Analysis
##Project Overview
This project analyzes Velocity Bikes sales data using SQL to answer practical business questions related to product performance, customer value, regional sales, marketing opportunities, and product strategy.
The project was developed as part of an SQL data-analysis exercise and demonstrates how fundamental SQL techniques can be applied to transform transactional sales data into actionable business insights.
##Business Objective
The primary objective is to use SQL-based analysis to answer questions such as:
•	Which products generate the highest revenue?
•	Which customers represent the highest-value customer segment?
•	Which states generate the most and least revenue?
•	Which products may require additional marketing attention?
•	Which products appear to be underperforming?
•	Does model year appear to influence product performance?
•	Which regions may offer opportunities for business expansion?
##Dataset
The analysis uses three relational tables:
###Customers
Contains customer-level information including:
•	Customer ID
•	Customer details
•	Location
•	Contact information
###Products
Contains product information including:
•	Product ID
•	Product name
•	Model year
•	Price
###Orders
Contains transactional information including:
•	Order ID
•	Customer ID
•	Product ID
•	Quantity
•	Price
•	Order date
Note: The dataset was provided for instructional purposes. The original dataset is not redistributed in this repository.
##SQL Techniques Used
The project focuses on fundamental SQL data-analysis techniques, including:
•	SELECT
•	WHERE
•	ORDER BY
•	GROUP BY
•	Aggregate functions
•	SUM()
•	AVG()
•	COUNT()
•	MIN()
•	MAX()
•	JOIN
•	LEFT JOIN
•	HAVING
•	LIMIT
•	Aliases
•	Basic calculated fields
##Business Questions
The SQL analysis is organized around several business questions:
1. Product Performance
Which products generate the highest revenue?
2. Customer Loyalty
Which customers generate the greatest revenue and could be targeted through a loyalty programme?
3. Regional Performance
Which states contribute the most and least to reported sales?
4. Marketing Opportunities
Which products should receive additional marketing attention?
5. Product Performance
Which products appear to have relatively low sales performance?
6. Model-Year Analysis
Does product model year appear to influence revenue performance?
7. Regional Expansion
Which states may represent potential opportunities for expansion?
##Key Findings
The SQL analysis identified several notable patterns.
###Product Performance
The Trek Slash 8 27.5 - 2016 appeared at the top of the submitted product-revenue ranking, followed by the Trek Conduit+ - 2016 and Trek Fuel EX 8 29 - 2016.
These products represent important candidates for continued inventory availability and targeted promotion.
###High-Value Customers
Customers 10, 75, 94, 6 and 16 appeared among the highest-revenue customers in the loyalty analysis.
These customers could form an initial high-value segment for customer-retention initiatives.
###Regional Performance
New York, California and Texas were prominent states in the submitted regional analyses. New York showed particularly strong reported revenue in the expansion analysis.
Regional decisions should, however, consider both revenue and customer/order volume rather than revenue alone.
###Model Year
The analysis did not demonstrate a simple relationship in which newer bicycle models consistently outperform older models.
This suggests that product-specific characteristics and customer demand may be more important than model year alone.
##Business Recommendations
Based on the SQL analysis:
1.	Prioritize high-performing products through targeted promotion and appropriate inventory levels.
2.	Develop a loyalty programme for high-value customers identified through revenue analysis.
3.	Investigate regional differences before allocating major expansion or marketing budgets.
4.	Avoid discontinuing products solely on low reported revenue. Unit sales, order frequency and profitability should also be considered.
5.	Use targeted marketing rather than blanket promotion, focusing on products and regions where additional demand could generate value.
6.	Validate SQL joins and aggregation logic before using analytical outputs for financial decision-making.
##Analytical Considerations
Some exploratory queries require further refinement before the resulting figures can be interpreted as audited business metrics.
In particular, revenue calculations can be affected by incomplete join conditions or grouping choices. These issues are documented in the accompanying business-insights report.
This is an important aspect of the project because reliable business analytics depends not only on writing syntactically correct SQL, but also on ensuring that table relationships and aggregation logic accurately represent the underlying business process.
##Repository Structure
velocity-bikes-sql-analysis/
│
├── README.md
├── sql/
│   └── FullName_Velocity_Bikes_Analysis.sql
├── report/
│   └── Velocity_Bikes_Business_Insights_Report.pdf
├── results/
│   └── SQL result screenshots
├── data/
│   └── README.md
└── .gitignore
##Future Development
This project provides a foundation for extending the analysis beyond SQL.
A future version could connect the SQL database to Python for:
SQL Database
      ↓
SQL Data Analysis
      ↓
Python
      ↓
Feature Engineering
      ↓
Machine Learning
      ↓
Business Prediction
Potential extensions include customer segmentation, sales forecasting and product-demand prediction.
##Project Context
This project demonstrates an initial step toward integrating database-driven data analysis with data science and machine learning workflows.
The immediate focus is SQL fundamentals; future development will explore how structured data stored in relational databases can feed analytical and machine-learning models.

