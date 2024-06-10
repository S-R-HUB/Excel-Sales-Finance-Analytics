# Excel: Sales and Finance Analytics
## Problem Statement:

AtliQ Hardwares is a hardware company which sells hardware devices and accessories. Their business model consists of manufacturing the devices and shipping it to their warehouses of different region and selling the items through offline and online retailers, distributors and from their authorised exclusive store. AtliQ Hardware has been piled up with excel files. They need insights from the excel files to improve specific areas in their business. The objective is to create sales and finance reports for AtliQ Hardware based on the requirements provided by them.


## Sales Analytics Overview:
This consists of the below reports:

1. [Customer Performance:](https://github.com/S-R-HUB/Excel-Sales-Finance-Analytics/blob/main/Customer%20Performance%20.pdf) Crafted a detailed report which provided an overview of the net sales by various customer during the last three fiscal years

2. [Market Performance vs Target:](https://github.com/S-R-HUB/Excel-Sales-Finance-Analytics/blob/main/Market%20Performance%20vs%20Target.pdf) Delivered a comparative overview of net sales with respect to targets of the different regions

***Purpose of Sales Analytics***: Helps business to track and evaluate their sales activities

***Importance of analyzing sales data***: To reveal the trends and patterns in the sales and indentify the Key Performance Indicators(KPIs)

***Role of the report***: Provides a detailed insight and helps business managers to take strategic decisions to increase the sales of the organisation in various regions

### Steps involved in creating the report

- Performed ETL operation using Power Query on data set including cleaning the data and loading to data model
- Listed the components required for creating report
- Created a date table which includes the date range and the fiscal year in Power Query
- Connected all the table and created relationship using data model 
- Created new measures using DAX in power pivot to build the report
- Enhanced the user experience of the report using conditional formatting



## Finance Analytics Overview:
This consists of the below reports:

1. [Profit and Loss(P&L) by Year:](https://github.com/S-R-HUB/Excel-Sales-Finance-Analytics/blob/main/Profit%20and%20Loss%20by%20Year.pdf) This report shows all the Profit & Loss metrics with respect to fiscal years

2. [Profit and Loss(P&L) by Quaters:](https://github.com/S-R-HUB/Excel-Sales-Finance-Analytics/blob/main/Profit%20and%20Loss%20by%20Quaters.pdf) Crafted Profit & Loss report with respect to months and Quaters

3. [Profit and Loss(P&L) by Market:](https://github.com/S-R-HUB/Excel-Sales-Finance-Analytics/blob/main/Profit%20and%20Loss%20by%20Market.pdf) Crafted Profit & Loss report with respect to market

***Purpose of Finance Analytics***: To measure financial performance, helps in decision making and enhance communication with stakeholders

***Importance of analyzing financial data***: Enables business to set benchmark against peers, helps in informed decision making, financial planning and budgeting and improving profitability

***Role of the report***: Project financial planning aligned with strategic goals, strengthening confidence in company's financial roadmap

### Steps involved in creating the report

- Created a reference fact table with additional costs coloumn using Power Query and performed ETL operation
- Listed the components required for creating report
- Summation of all the cost to obtain total COGS in power pivot
- Created separate coloumns in power pivot to obtain the fiscal month and fiscal month number to generate Quaters using DAX formulas
- Created new measures using DAX in power pivot to get the gross margin percent
- Enhanced the user experience of the report using conditional formatting
