# Power-BI-Customer-Churn-Analysis

### Project Overview

In this Power BI case study, I investigate Databel's customer churn rates as a subscription-based business. Reducing customer churn is a top priority for Databel, and my task is to explore the data and provide insights to help the company understand and mitigate customer churn.

### Data Sources

I will be working with a dataset from the telecom company Databel: the 'Databel - Data' file. By analyzing this dataset, my goal is to gain insights into Databel's customer churn rates, as reducing churn is a critical priority for this subscription-based business. Through exploring and visualizing data from this file, I aim to provide actionable recommendations to help Databel better understand and mitigate customer churn.

### Tools Used (Power BI)

- DAX Concepts: Calculated Column, Custom Column, `IF()`.
- Power Query: Created Measures.
- Report Pages and Data Visualization.

 ### Data Transformation/ Cleaning

  - Created two (2) measures to check if the count of ID's is equal to the count of unique customer ID's. The two measures created are `Number of Customers` and `Number of Unique Customers`.
  - Used an `IF()` statement to convert `Churned Label` column that has a Return response of YES and NO into a `Churned` column that contains a numeric value, 1 for customer churned and 0 for customers who did not.
  - Created a measure for `number of churned customers`.
  - Calculated the `Churn Rate` and formatted it as a percentage.
 
### Exploratory Data Analysis (EDA)

EDA involved exploring the data to answer key questions such as:

1. What is the customer churn rate?
2. What are the different reasons customers churned?
3. What is the churn rate by state?
4. Any other relevant data-driven insight discovered during analysis.

### Results/ Findings


