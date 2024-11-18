# PowerBI-Analytics-AdventureWorks

PowerBI-Analytics-Adventure Works
This PowerBI project analyses the performance of a fictional store chain with multiple stores across the World. The goal is to illustrate PowerBI's capabilities in analysing and reporting on sales data, sale insights, and key performance indicators.

# Power BI report
You can view the Power BI report here.

Data Collection
The project incorporates data from 5 tables, featuring sales data comprising over 60,000 rows of transactions. The dataset covers various dimensions such as Order Date, Order Quantity, Total Sales, Product Details, Product Costs, Customers, and Store Locations. This dataset constructed, drawing inspiration from Microsoft's AdventureWorks sample database.


Data Model
The data model is structured as a star schema, which facilitates efficient analysis and reporting. The central fact table contains sales data, and it is connected to dimension tables such as sales territory, sales product and customer. 

Report Pages
The PowerBI report provides 5 main pages:

Overview Dashboard: Depicting sales trends over time, and key information for executives.

Total Sales by Year: Comparison of Total Sales, Total Margin and Count of Sales Orders between different years.

Product Details: Information about product sales details by subcategory, total sales and YTD sales

Sales Region: In-depth exploration of total sales by country. 

Margin percentage by Country and Product Category: Comparison of sales in each country by product category

Features of the Report
Parameters
The report uses parameters to allow users to dynamically interact with visuals. parameter-example

Navigation Buttons
The report includes navigation buttons between pages, enhancing user experience and facilitating seamless exploration of different aspects of the data.

navigation-buttons

Drill Up and Drill Down
Users can drill up or down to explore data at different levels of granularity. For example, drilling down from yearly sales to monthly or weekly sales.

KPIs Compared to Previous Month
Key Performance Indicators (KPIs) are displayed with a comparison to the previous month. This allows users to quickly assess performance trends and variations.

