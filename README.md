# PowerBI-Analytics-AdventureWorks

PowerBI-Analytics-OzStores
This PowerBI project analyses the performance of a fictional store chain with multiple stores across the World. The goal is to illustrate PowerBI's capabilities in analysing and reporting on sales data, sale insights, and key performance indicators.

# Power BI report
You can view the Power BI report here.

Data Collection
The project incorporates data from 15 tables, featuring sales data comprising over 60,000 rows of transactions. The dataset covers various dimensions such as Order Date, Order Quantity, Total Sales, Product Details, Product Costs, Customers, and Store Locations. This dataset constructed, drawing inspiration from Microsoft's AdventureWorks sample database.


Data Model
The data model is structured as a star schema, which facilitates efficient analysis and reporting. The central fact table contains sales data, and it is connected to dimension tables such as sales territory, sales product and customer. 

Report Pages
The PowerBI report provides 4 main pages:

Overview Dashboard: Depicting sales trends over time, and key information for executives.

Sales Regiion: Comparison of sales performance among different stores based on locations.

Customer: Identification of customer segments based on purchasing behavior. customer-analysis

Product Detail: In-depth exploration of the selected product. product-details

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

Getting Started
You can view the Power BI report here.

To explore the PowerBI report, follow these steps:

Clone the repository to your local machine.

git clone https://github.com/Andy-Hoang/PowerBI-Analytics-OzStores.git
Adjust data source path.

Open the PowerBI project file using PowerBI Desktop.
Open Power Query Editor and locate the query containing the data source path. It might look like the following:
 = Csv.Document(File.Contents("<your local csv file path>"),[Delimiter=",", Columns=6, Encoding=65001, QuoteStyle=QuoteStyle.None])
Replace <your local csv file path> with the actual path to your local CSV file.
Feel free to reach out if you encounter any issues or have further questions!
