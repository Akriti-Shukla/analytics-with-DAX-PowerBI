# Analytics with DAX - Power BI

This project demonstrates advanced analytics using DAX (Data Analysis Expressions) in Power BI to uncover insights from global sales data. By applying key DAX concepts and creating both calculated columns and dynamic measures, the analysis explores performance across countries, time periods, customer demographics, and regional trends.

## Measures Created :

![Calculated Measures](https://github.com/user-attachments/assets/6060e831-2817-4623-afe9-a5f298de2ae4)


## Key Concepts Applied

✔️ DAX Fundamentals  
✔️ Row Context & Navigation Functions  
✔️ CALCULATE Function  
✔️ Time Series Analysis  
✔️ Semi-Additive Measures  
✔️ Context Transition  

## Use Case

The dataset includes sales, customer, product, and date information across multiple regions. This project aims to:

- Break down customer demographics
- Analyze sales performance by country and time
- Measure profitability and transaction volumes
- Build time intelligence reports (YTD, Prior Month/Year)
- Apply semi-additive logic for inventory metrics

## Key Calculated Columns

- **Full Name**: Combines first and last name from the Customer table  
- **Age Breakdown**: Categorizes customers into age groups (18–34, 35–44, etc.)  
- **Month-Year**: Converts date into "mm-yyyy" format for reporting  
- **Temperature Key**: Combines region and month for analytical grouping  
- **Total Transactions**: Counts transactions per region  
- **Region Volume**: Classifies regions into High/Medium/Low volume categories  
- **Last Order Date**: Retrieves the most recent order per customer  

## Highlighted Measures

- **Total Sales, Cost, Profit, and Profit Margin**  
- **Total Sales by Country, Region, Year (using CALCULATE)**  
- **Percent of Total Sales**  
- **Year-to-Date (YTD), Fiscal YTD, Prior Year, Prior Month Sales**  
- **Inventory Closing and Opening Balances**  

## Special Techniques Used

- **CALCULATE with ALL, REMOVEFILTERS, and conditions**  
- **Time Intelligence with TOTALYTD, SAMEPERIODLASTYEAR, DATEADD**  
- **Context Transition for row-to-filter context conversion**  

This repository offers a strong foundation for anyone looking to deepen their understanding of DAX and create scalable, dynamic, and insightful Power BI dashboards.


