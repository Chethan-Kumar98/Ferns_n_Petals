# Ferns_n_Petals

Project Overview:
This project focuses on analyzing sales, customer, and order data from the Ferns N Petals store (FNP), downloaded from Kaggle. The dataset consists of three key files: customer data, product data, and order data. The goal of this project is to clean, transform, and analyze this data using Excel to extract valuable business insights. The analysis involves creating an interactive dashboard to visualize key performance indicators (KPIs) and trends such as revenue by product, customer behavior, and order patterns.

Key Features:

Data Import and Transformation:

1. Importing Data: The three separate Excel files containing customer, product, and order data were imported into a new Excel workbook for unified analysis.
2. Power Query Editor: Data cleaning and transformation were performed using Power Query. Key steps included:
3. Data Cleaning: Removed blank rows, handled duplicates, and ensured that there were no missing or incorrect values.
4. Data Type Correction: Ensured that each column had the correct data type (e.g., dates, currency, text) for proper analysis.
5. Calculated Columns: New columns were created for deeper insights, including:
   1. Total Revenue: Revenue for each order was calculated by multiplying the quantity of the product by its unit price.
   2. Day Extraction: Extracted the day from the date column to identify trends by day of the week.
   3. Hour Extraction: Extracted the hour from the time column to determine peak sales hours.

Data Modeling and Relationship Creation:
Data Model: The cleaned data was loaded into Excel’s Data Model, and relationships between the three datasets (customers, products, and orders) were established using common columns (such as CustomerID and ProductID).
This allowed for more powerful and interactive analysis across the different datasets.

Data Analysis:
Pivot Tables and Pivot Charts were utilized to analyze the data in detail and extract meaningful insights:
1. Month-wise Revenue: Analyzed revenue trends over different months to identify seasonal variations and peak sales periods.
2. Product-wise Revenue: Identified the best-selling products based on total revenue generated, helping to inform product marketing strategies.
3. Revenue by Occasion: Analyzed sales based on various occasions (e.g., birthdays, anniversaries) to understand which occasions drive the most sales.
4. Customer Spend Analysis: Analyzed customer spending behavior, identifying high-value customers and trends in purchasing patterns.
5. KPI Analysis: Key metrics were calculated to track business performance, including:
   Total number of orders.
   Total revenue.
   Average delivery days.
   Average customer spend.
   Interactive Dashboard:

An interactive dashboard was created within Excel using charts, KPIs, and slicers for easy exploration of the data:
1. Charts: Various charts were created, including bar charts, pie charts, and line charts to visualize revenue by product, revenue trends over time, and more.
2. Key Performance Indicators (KPIs): The dashboard highlights important KPIs such as total revenue, total orders, and average delivery days for a quick overview of performance.
3. Slicers: Interactive slicers were added to allow users to filter the data by product, customer, occasion, and time period (e.g., by month, by year), enabling dynamic analysis.
4. Timeline: A timeline was included to filter and analyze data based on specific time periods, such as monthly or yearly trends.

Insights and Findings:
1. Sales Trends: The analysis uncovered trends in sales performance over different months and product categories, helping to identify the most profitable products and peak sales periods.
2. Customer Insights: Identified high-value customers and analyzed their spending patterns, which could be used for targeted marketing efforts and personalized promotions.
3. Order Efficiency: Analyzed average delivery days and the impact of delivery times on customer satisfaction and sales performance.
4. Occasion-Based Sales: Understanding which occasions (e.g., Valentine's Day, Diwali) contributed the most to revenue helped optimize product offerings during peak seasons.

Tools and Technologies Used:

Microsoft Excel: For data cleaning, transformation, analysis, and dashboard creation.
Power Query: Used for data transformation and cleaning.
Data Model and Relationships: Created to connect and analyze the data across multiple files.
Pivot Tables and Pivot Charts: Used to summarize and analyze data interactively.
Excel Dashboards: Created for a visually appealing representation of key business insights.

Project Goal:
The goal of this project was to clean and analyze the FNP store's sales, customer, and order data to uncover valuable insights. The project aimed to create an interactive dashboard for business stakeholders to monitor key metrics, track performance, and make informed decisions about product offerings, customer engagement, and operational efficiency.

Project Deliverables:

Cleaned and Transformed Dataset: Ready for analysis and decision-making.
Pivot Tables and Pivot Charts: Used to analyze data and generate key insights.
Interactive Dashboard: With visualizations, KPIs, and slicers for dynamic filtering and analysis.

Future Enhancements:

Advanced Analytics: Further analysis could include predictive models for forecasting sales, customer behavior analysis, and demand forecasting.
Automated Reporting: Set up automated reports for real-time monitoring of sales and KPIs.
Power BI Integration: Moving the dashboard to Power BI for enhanced visualizations and real-time data analysis with more interactive capabilities.
