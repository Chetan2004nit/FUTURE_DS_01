Business sales Dashboard Analysis 

Overview :
 This project aims to analyze sales data to uncover trends and patterns in sales performance, customer demographics, and product popularity. Using SQL for data processing and Power BI for visualization, the project provides a comprehensive view of sales metrics.

Project Structure ->>

SQL Database :
 For data loading, cleaning, and querying.

Power BI :
 For interactive dashboard creation and data visualization.

Dataset :

 The dataset includes the following fields->>

Sales Details :
 Transaction ID, Date (Year, Month, Day)

Customer Information :
 Region, Country, Customer Segment

Product Information :
 Product Category, Sub-category, and Product ID

Sales Metrics :
 Units sold, Total Revenue, Profit
Additional Information: Discounts, Cost per item

SQL Implementation ->>

Database Creation :
 sales_analysis

Table Setup :
 sales_data

Data Loading :
 Using SQL’s COPY command for importing CSV data.

Data Cleaning Steps :

 Identifying and handling missing values.
Removing incomplete records.
Standardizing text fields and currency formats.

Data Queries for Analysis ->>

Total Sales :
 Sum of total revenue.

Total Profit :
 Calculated profit across all transactions.

Temporal Sales Analysis :
 Yearly and monthly revenue trends.

Top-Selling Products :
 Identifying the most popular products.

Customer Segment Analysis :
 Analyzing revenue by customer segment and region.

Power BI Visualization :

 In Power BI, the following visuals were created

Sales Over Time: 
 Revenue and profit trends by month and year.

Geographic Distribution: 
 Sales performance by region and country.

Product Analysis:
 Best-selling product categories and sub-categories.

Customer Segment Performance: 
 Revenue by customer segment.

→Insights :

 
Ans1: The peak sales period is in Q4 of 2020, especially December, possibly due to holiday season shopping.

Top Categories or Regions Driving Most Revenue

Ans3:
3D Systems Cube Printer, 2nd Generation, Magenta	14,334.89
Canon imageCLASS 2200 Advanced Copier	14,076.82
Hewlett Packard LaserJet 3310 Copier	13,837.73

Ans2:Most revenue
By Category:
Category	Revenue (USD)

Office Supplies	643,707.69
Technology	470,588.00
Furniture	451,508.65


Office Supplies lead in overall revenue.
By Region:

Region	Revenue (USD)

West	522,441.05
East	450,234.67
Central	341,007.52
South	252,121.08

