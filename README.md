# LITA Capstone Project

### Project Title: Sales Performance Analysis 

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools Used](#tools-used)

[Data Cleaning and Preparation](#data-cleaning-and-preparation)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Visualization](#data-visualization)


### Project overview 
- - - 
The aim of this Data Analysis project is to generate insight into the sales performance of a retail store from the past year to the month of August of this current year(2024). we want to achieve this by analysing the different informations in the dataset received. Additionally we will obtain sufficient information to make rational decisions, which will allow us to use the information to create simple and captivating narratives about our data and determine its best performance.


### Data Sources
- - -
The main source of data used in this project is Sales Data.xls and this was gotten from The Incubator Hub solely for the purpose of the Capstone Project.     


### Tools Used
- - -
- MIcrosoft Excel  [Download Here](https://www.microsoft.com)
  1. for Data Cleaning
  2. for  Analysis
  3. for Visualization
     
- SQL- Structured Querying of Data 
  
- Power BI   [Download Here](https://www.microsoft.com)
  1. for Data Cleaning
  2. for Creating Report
  3. for Visualization
- Github for Portfolio building
  

### Data Cleaning and Preparation
- - -
During the first stage of the data cleaning and preparation we carried out the following tasks: 
1. Data loading  and examination
2. Handling missing variables
3. Removal of duplicates data
4. Data cleaning and formatting   


### Exploratory Data Analysis
- - -
This process involved the exploration of the data to create certain reports and provide answers to some questions about the data such as;
- summary of total sales by product, region, and month using pivot tables.
- what is the average sales per product?
- what is the total reveenue by region?
- retrieve the total sales for each product category.
- find the number of sales transactions in each region.
- find the highest-selling product by total sales value. 
- calculate total revenue per product.
- calculate monthly sales totals for the current year.
- find the top 5 customers by total purchase amount.
- calculate the percentage of total sales contributed by each region.
- identify products with no sales in the last quarter.


### Data Analysis 
- - -
This is where we include some basic lines of code or queries or even 

```SQL
SELECT *FROM [dbo].[SALES DATA]

SELECT product,SUM (totalrevenue) as totalsales from[dbo].[SALES DATA]
GROUP BY product

SELECT totalrevenue from [dbo].[Sales data]
GROUP BY  orderdate
ORDER BY orderdate desc

 

### Data Visualization
- - -  






