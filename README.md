# AtliQ Business Insights 360

## Project Overview

AltiQ Hardware, a fast-growing company expanding globally, specializes in selling computers and accessories through three main channels: retailers, direct sales, and distributors.

Despite its growth, the company faced unexpected losses after opening a store in America. These setbacks were identified through surveys, intuition, and basic Excel analysis. With competitors boasting robust analytics teams, AltiQ Hardware recognizes the urgent need to develop its analytics capabilities to thrive in the industry.

To surpass competitors and enable data-driven decision-making, the company has decided to implement Power BI for analytics. This project aims to provide stakeholders with insights into finance, sales, marketing,
 and supply chain, ensuring informed decisions at all levels.I worked on this project by following the Codebasics PowerBi Course, 

Here is my report link -(https://app.powerbi.com/view?r=eyJrIjoiY2I5NmFmNDktNjBlYS00ODlkLWI4ZWEtM2ZkODE4MmQ3MmFiIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)


## Datasets:

Before diving into analysis, understanding the datasets is crucial. The datasets consist of two tables:

**Dimension table:** Static data like customer and product details.

**Fact table:** Transaction data.

gdb041:
* dim_customer
* dim_market
* dim_product
* fact_forecast_monthly - This table is used to forecast the customer’s need in advance, which can help in Higher customer satisfaction and reduced cost in warehouses for storage purposes
* fact_sales_monthly - This table is more or less is same as the fact_forecast_monthly table, but the last column has the value of the sold quantity instead of the forecast value.

gdb056:
* freight_cost
* gross_price
* manufacturing_cost
* Pre_invoice_dedutions
* Post_invoice_deductions


### Importing Data and Data Modeling:

Data was imported from MySQL into Power BI, and a data model was created after cleaning and transforming the data. But why data modeling is very important for analysis right??

If you break down the whole work of a data analyst then you will come up with 4 steps of work 

✅ Data Extract ---> ✅ Data Cleaning---> ✅ Data Modelling ---> ✅ Data Analysis

See you can't skip the 3rd step if you want to reach the last step (analysis part), 
Data modeling is essential because it lays the foundation for reports. All visuals are built upon the data model, and poor modeling can affect report performance.

In this project, we have followed the Snowflake schema data modeling method. 


![Data Model](https://github.com/user-attachments/assets/3ea76176-8315-44ae-8ab5-27277a934402)


## Power BI Dashboard Overview:

The dashboard comprises six pages-->

### Home Page View: A landing page with buttons to navigate to different pages.

![Home Page](https://github.com/user-attachments/assets/7155481f-73f5-4793-ac29-d4b7fab79fd4)


### Finance Page View: Focuses on improving financial planning, budgeting processes, and cost control. Includes Profit and Loss statements, Top and Bottom Products and Customers by Net Sales, and more.

![Finance View page](https://github.com/user-attachments/assets/caef4b6f-4652-46b3-88ed-b2aa2fc5027f)


### Sales Page View: Aims to increase sales revenue and market share. Features Customer performance by Net Sales, Gross Margin, Gross Margin %, and more.

![Sales View Page](https://github.com/user-attachments/assets/8f5a4adc-33b3-4610-87b1-834fc9cd11e7)



### Marketing Page View: Aims to increase brand visibility and customer engagement. Provides Segment Performance by Gross Margin% and Net Profit%, and more.

![Marketing View page](https://github.com/user-attachments/assets/28042eba-1717-4955-83db-e2c382fbb22d)


### Supply Chain Page View: Aims to optimize inventory management and enhance supplier relationships for cost savings. Includes details about Forecast Accuracy, Net error, and more.

![Supply Chain View Page](https://github.com/user-attachments/assets/4bc15e3d-8af8-4f61-b2c0-7a7d6af7b8da)


### Executive Page View: Provides an overview of the organization's performance for top management. Includes Net Sales, Gross Margin%, Net Profit%, Revenue Contribution by channel, Top 5 Customer and Product, Sub Region performance, and more.

![Executive View page](https://github.com/user-attachments/assets/034b5810-0527-4ef3-93c3-0a27e2a69646)


## Skills Learned:

During this project, I learned:
Power BI fundamentals,
Calculated columns and DAX measures,
Data Modeling, Data Cleaning, Bookmarks, Conditional formatting,
Custom Tooltip usage, Dynamic Title Creation, and more.

### Tools Used:

SQL, Power BI Desktop, DAX language, DAX studio (to reduce file size), Project Charter file.

### Business Terms Learned:

Gross Margin, Gross Margin %, Gross Sales, Gross Sales %, Pre-invoice deductions, Post-invoice deductions, Net sales, Net Invoice Sales, Net Profit, Net Profit %, COGS (cost of goods sold), YTG (year to go), YTD (year to date), Direct, Retailer, Consumer, Distributors.

## Conclusion :

This report empowers decision-making based on data, addressing numerous "why" questions across various scenarios. It serves as a tool to extract insights and guide actions, ultimately aiming to enhance AltiQ's profitability through data-driven decisions.
