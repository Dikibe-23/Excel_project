# COFFEE SALES ANALYSIS USING EXCEL

## About the project
The aim of this project is to perform sales analysis with the aid of MS Excel. The data set provided in the current repository.

## Table of Contents
1. [About the project.](#About-the-project)
2. [KPI.](#KPIs)
3. [Tool.](#tools)
4. [Steps.](#steps)
5. [Insights.](#insights)

## KPIs
1. YoY and MoM Sales.
2. Customers with the most purchases.
3. Country with the most patronage.
4. Which coffee type sells the most.

## Tools
1. MS Excel.

## Steps
1. <b>Data Connection:</b> First, we connect to our data source or database and perform data ETL or ELT with the aid of SQL to MS Excel.
2.	<b>Data Cleaning:</b> In this step, we identify features of interest, deal with missing data points, perform data quality checks and populated the ‘Orders’ table with entries from the ‘Customer’ and ‘Products’ table.
3.	<b>Dashboarding/Insight Generation:</b> In this step, we visualized some KPIs of the business from the data in order to generate insights and have an overview of the business performance.

## Formula used
```
   =IF(XLOOKUP([@[Customer ID]];customers!$A$2:$A$1001;customers!$C$2:$C$1001;;0)=0;"";XLOOKUP([@[Customer ID]];customers!$A$2:$A$1001;customers!$C$2:$C$1001;;0))
   =INDEX(products!$A$1:$G$49;MATCH(orders!$D3;products!$A$1:$A$49;0);MATCH(orders!I$1;products!$A$1:$G$1;0))
   
```
## Insights

1.	Between year 2019 and 2020, coffee type Excelsa and Arabica were the most sold coffee type.
2.	We notice that over the years, Excelsa and Liberica have been the most purchased coffee type.
3.	The United States has the most coffee sales.
4.	We have also been able to find the top 5 customers.



   
