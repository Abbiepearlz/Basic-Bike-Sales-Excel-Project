# Basic Bike Sales Analysis

### Project Overview

This is a data analysis project aim to provide basic insights into the sales performance of a bike sales company using Microsoft Excel.The project's objective was to gain insights into the sales performance, customers profiles, and profitability of the bike products. The analysis was conducted to assist in making data-driven decisions to improve business strategies and determine areas for growth. The entire project dataset which comprises of 1001 rows and 14 columns is completed using MS Excel concepts such as data cleaning, pivot tables and dashboard. 

### Data Sources
The Primary dataset used for this analysis is the "bike_sales_data.csv" file , containing deatiled information about each bike sale made by the company.

### Tool
Microsoft Excel - [Download Here](https:/microsoft.com)

### Data cleaning / Preparation 

In the initial data preparation phase,i performed the following tasks 
1. Data loading and inspection 
2. Removed duplicates
3. Replaced abbreviations (Find and replace)
4. Handling blank spaces
5. Created custom columns (Age Range) to extract additional information from the dataset.
6. Created an interactive dashboard in Excel with slicers, which allows users to interact with the data.

### Exploratory Data Analysis
1. This involved exploring the sales data to answer few key questions such as:
2. What are the number of males and females that purchased the bike at that particular time?
3. Is there any influence of commuting distance on bike purchase?
4. What are the average income of buyers and non buyers and its influence on purchase.
5. What are the age range of customers that puchased the bike?

### Data Analysis
Functions Used :

```Excel
Syntax =COUNTIF(C:C,"Female")

Syntax "=IF(L2 >54,"Old", IF(L2>30,"Middle Age", IF(L2<=30 ,"Adolescents","Invalid")))
```

### Results 

The analysis results are summarized as follows:

1. Males who purchased bikes had higher incomes than those who didn't, suggesting income influences bike purchasing decisions

2. The average income of Males who purchased is $70,625 while average income for females who purchased the bike is $66,000. So,the company had more male buyers than females.
   
3. People in the Middle Age group (31-54 years) purchased more bikes as compared to the Adolescent and Old age groups, suggesting that age is also an influce to bike purchase.
   
4. Customers in shorter commutes (0-1 miles) tend to purchase bikes more than customers in longer commutes (10 miles +), which suggest that cummute distance is also an influence in bike purchase.

5. A decrease in bike purchases was observed with an increase in the number of children.

### Recomendation.

Based on the analysis , i recommend the following actions :

- Improve marketing techniques, such as focusing on enticing workers and attracting people who have longer commutes.






