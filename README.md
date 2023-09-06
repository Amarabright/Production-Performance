# Production-Performance Optimization


This is a project that shows my ability to use DAX Suggestion and other AI visuals for visualization in PowerBI. Although data is queried from the Adventure Works DW database. 
*(The  picture below is gotten from bike Europe website)*
![](BIKEEUROPE.jpg)

## INTRODUCTION
It is important for any manufacturing company, to ensure efficient production performance in order to fulfill client demands, optimize resources, and maximize profits. This created the need for this analysis as it will offer significant insights into production performance across multiple dimensions

The Manufacturing Performance report can be used by the management team of the company to monitor and evaluate key production indicators, identify bottlenecks, and make data-driven choices to optimize operations. 


## PROBLEM STATEMENT
To provide insights into production performance by various categories and time periods.

## Skills and Concepts demonstrated:
 
 - SQL (Select, alias, Views)
 - PowerBI concepts like:
   - Creating key performance indicators (KPIs) and other business calculations using DAX Suggestion(CO-PILOT),
   - Data Modelling,
   - Measures,
   - filters,
   - tooltips, 
   - Page buttons,
   - Data Visualization
  
## Data Source:

The data used for this work is obtained from AdventureWorks2019 database tables - Production.Product, Production.BillOfMaterials, Production.WorkOrder, and  Production.WorkOrderRouting.
  - You can find a link to get started with installation and restoration of the database to your local machine.  [here:](https://youtu.be/VpY0Q_kwtIw) 
 ---

## Data Transformation:
- I wrote just a few queries in the Database on SQL Management Studio to view every detail in the tables. 
![](Prod1.png)

- Then I imported the tables into my PowerBI desktop app 
![](prod2.png)

- I transformed the data in Power Query, checked for Colum quality, consistent or appropriate data types
- I began writing several Dax and creating measures and calculated columns to get the right metrics for the Inventory analysis.
- I also created the calendar table
- The queries I wrote on SQL are compiled and also uploaded here in this repository as "ProductionOptimizationQuery.sql"
---

## Data Modelling:
The intelligence in PowerBI makes it such that tables are automatically joined by creating relationships with them. However, as someone who understands the dataset and wants to get specific insights and information. I had to create other relationships and measures to enable me. so I did another model. I created 7 dimension tables and 2 fact tables as I hoped for a Star Schema.

Created Model               |        Automated Model
:------------------------:  | :----------------------------------:
![](ProdTable.png)          | ![](prod3.png)

---
## Data Analysis
