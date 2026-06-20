Customer Shopping & Revenue Dashboard
Overview
This project is an Excel-based retail analytics dashboard built using a customer shopping transaction dataset. The objective of the project is to transform raw shopping data into a business-friendly dashboard that helps analyze revenue performance, category trends, shopping mall performance, payment preferences, and customer purchase behavior.
The project demonstrates a complete Excel analytics workflow, including data cleaning, helper column creation, KPI calculation, pivot table analysis, and dashboard development.
________________________________________
Business Problem
A retail shopping mall group wants to analyze customer shopping behavior across product categories, shopping malls, payment methods, and customer age groups. Although transaction data is available, management cannot quickly identify which categories drive the most revenue, which malls perform best, or which customer segments contribute the most sales.
To solve this problem, an interactive Excel dashboard was developed to summarize retail performance and customer purchase insights in a single view.
________________________________________
Objective
Build an interactive Customer Shopping & Revenue Dashboard in Microsoft Excel to monitor and analyze:
•	Total Orders
•	Total Customers
•	Total Revenue
•	Average Order Value
•	Total Quantity Sold
•	Average Customer Age
•	Category-wise Revenue
•	Mall-wise Revenue
•	Payment Method Usage
•	Age Group Shopping Behavior
•	Gender-wise Revenue
•	Spend Segment Analysis
•	Monthly Sales Trend
________________________________________
Tool Used
•	Microsoft Excel
________________________________________
Dataset Information
Dataset Name
customer_shopping_data.csv
Dataset Size
•	500 rows (portfolio sample used for project)
•	10 original columns
Original Dataset Columns
•	invoice_no
•	customer_id
•	gender
•	age
•	category
•	quantity
•	price
•	payment_method
•	invoice_date
•	shopping_mall
________________________________________
Workbook Structure
The Excel workbook contains the following sheets:
1.	Raw_Data – original imported dataset

2.	Cleaned_Data – cleaned data with helper columns

3.	KPI_Calculations – KPI formulas and summary metrics

4.	Pivot_Tables – pivot tables for analysis

5.	Dashboard – final interactive Excel dashboard
________________________________________
Data Preparation and Helper Columns
To make the raw dataset analysis-ready, the following helper columns were created in the Cleaned_Data sheet:
•	Sales_Amount – calculates transaction revenue using quantity × price

•	Age_Group – groups customers into age bands

•	Spend_Segment – classifies transactions by spending level

•	Quantity_Group – groups orders based on item count

•	Month – extracts month from invoice date

•	Month_No – supports chronological month sorting

•	Year – extracts year from invoice date

•	Customer_Type – classifies transactions as High Value or Regular

•	Order_Size – classifies orders as Bulk Order or Normal Order
These helper columns improved customer segmentation, revenue analysis, and dashboard reporting.
________________________________________
KPIs Built
The following KPIs were created in the KPI_Calculations sheet:
Main KPIs
•	Total Orders
•	Total Customers
•	Total Revenue
•	Average Order Value
•	Total Quantity Sold
•	Average Customer Age
Additional KPIs
•	Female Revenue
•	Male Revenue
•	Credit Card Orders
•	Cash Orders
•	High Value Orders
•	Bulk Orders
________________________________________
Pivot Table Analysis
Multiple pivot tables were created in the Pivot_Tables sheet to analyze the data from different business perspectives.
Pivot tables included:
•	Category-wise Sales
•	Mall-wise Revenue
•	Payment Method Usage
•	Age Group-wise Sales
•	Gender-wise Revenue
•	Month-wise Sales Trend
•	Spend Segment Analysis
•	Quantity Group Analysis
•	Mall vs Category
•	Payment Method vs Revenue
•	Customer Type Revenue
•	Order Size Analysis
________________________________________
Dashboard Features
The final Dashboard sheet includes:
KPI Cards
•	Total Orders
•	Total Customers
•	Total Revenue
•	Average Order Value
•	Total Quantity Sold
•	Average Customer Age
Charts
•	Category-wise Revenue
•	Mall-wise Revenue
•	Payment Method Distribution
•	Age Group Revenue
•	Gender-wise Revenue
•	Spend Segment Revenue
•	Monthly Sales Trend
Filters / Slicers
•	Category
•	Gender
•	Shopping Mall
•	Payment Method
________________________________________
Business Insights Generated
This dashboard helps answer key retail business questions such as:
•	Which product categories generate the highest revenue?
•	Which shopping malls perform best?
•	Which age groups contribute the most sales?
•	Which payment methods are used most often?
•	How does monthly revenue change over time?
•	Do high-value transactions contribute significantly to total sales?
________________________________________
Skills Demonstrated
This project demonstrates:
•	Excel data cleaning
•	Helper column creation
•	KPI design and calculation
•	Pivot table analysis
•	Pivot chart creation
•	Dashboard design
•	Customer segmentation
•	Retail analytics
•	Business storytelling
________________________________________
Project Workflow
The project was completed using the following workflow:
Raw_Data → Cleaned_Data → KPI_Calculations → Pivot_Tables → Dashboard
1.	Imported the shopping dataset into Raw_Data

2.	Cleaned and transformed the data in Cleaned_Data

3.	Created helper columns for segmentation and trend analysis

4.	Built KPI metrics in KPI_Calculations

5.	Created pivot tables in Pivot_Tables

6.	Designed the final interactive dashboard in Dashboard
________________________________________
Resume-Ready Project Summary
Developed an interactive Customer Shopping & Revenue Dashboard in Microsoft Excel to analyze retail sales, customer shopping behavior, mall-wise revenue, category performance, and payment trends. Built a complete Excel analytics workflow involving data cleaning, helper columns, KPI calculations, pivot table analysis, and dashboard design to generate business insights for retail decision-making.
________________________________________
Files in This Repository
•	Customer_Shopping_Revenue_Dashboard.xlsx
•	README.md
•	dashboard_screenshot.png
________________________________________
Author
Indhu Prasath
