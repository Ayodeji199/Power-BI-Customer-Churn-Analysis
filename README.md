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

![image](https://github.com/user-attachments/assets/15759c68-c09f-4539-bbbc-cef301747229)

The dashboard provides a comprehensive overview of customer churn analysis for Databel, presenting key metrics and visualizations that reveal patterns and potential areas for improvement. Here is a detailed analysis and insights generated from the dashboard:

- Key Metrics:

Total Number of Customers: 6,687

This is the total customer base being analyzed.

Churn Rate: 26.86%

This indicates that approximately 27% of the customers have left the service. A churn rate close to 27% is relatively high and suggests significant issues with customer retention.

Number of Churned Customers: 1,796

Out of the total customer base, 1,796 customers have churned.

Churn Reasons:
The bar chart on the left side of the dashboard breaks down the reasons for churn:

Top Reasons:

Competitor made better offer (20%): This is the most significant reason for churn, indicating that competitors are offering more attractive deals.
Competitor had better deals (15%): Another major reason, reinforcing that competitive pricing or offerings are leading to customer losses.
Attitude of support person (13%): A significant number of customers are dissatisfied with the support they receive, highlighting an area for improvement in customer service.
Don’t know (11%): A substantial portion of customers were unsure why they churned, suggesting potential gaps in customer feedback mechanisms or dissatisfaction with multiple aspects of the service.
Less Common Reasons:

Product dissatisfaction, network reliability, price too high, service dissatisfaction, etc.: These reasons, though less common individually, collectively account for a notable percentage of churn.
Customer Segmentation by Churn Category:
Competitor (53.56%): The largest segment, showing that over half of the churned customers left due to better competitor offerings.
Attitude (17.95%): Indicates significant churn due to customer service issues.
Dissatisfaction (12.01%) and Price (12.03%): Both are substantial categories, showing that product satisfaction and pricing are critical factors.
Other (4.45%): Miscellaneous reasons, suggesting a variety of less common factors contributing to churn.
Customer Segmentation by Contract Type:
Month to Month (62.87%): The majority of customers are on flexible contracts, which might make them more susceptible to churn.
Two Year (22.14%): A smaller segment, potentially indicating more stable customers.
One Year (14.98%): The smallest group, but still significant.
Geographic Distribution of Churn:
The map shows that churn is spread across the United States, with varying densities.
Higher Churn Areas: Larger green dots indicate regions with higher churn rates, often correlating with more populous areas.
Insights: Regions with higher churn may require tailored retention strategies, considering local competition and market conditions.
Insights and Recommendations:
Competitive Analysis and Response:

Insight: A significant portion of customers are leaving due to better offers from competitors.
Recommendation: Conduct a detailed competitive analysis to understand the specific offers and strategies of competitors. Develop counter-offers or enhance current packages to retain customers.
Enhance Customer Service:

Insight: Customer service issues are a major reason for churn.
Recommendation: Invest in customer service training and improve support processes. Implement regular feedback loops to understand customer grievances and address them promptly.
Flexible Contract Incentives:

Insight: Customers on month-to-month contracts are more prone to churn.
Recommendation: Introduce incentives for month-to-month customers to switch to longer-term contracts, such as discounts, additional benefits, or loyalty programs.
Targeted Regional Strategies:

Insight: Churn rates vary significantly by region.
Recommendation: Develop region-specific retention strategies. For high-churn areas, consider localized promotions, better service coverage, or enhanced customer engagement initiatives.
Product and Service Improvements:

Insight: Product dissatisfaction and service issues are notable reasons for churn.
Recommendation: Continuously improve product offerings and service reliability. Consider customer feedback for product development and enhancement.
Price Sensitivity Adjustments:

Insight: Pricing is a critical factor for churn.
Recommendation: Review pricing strategies and consider introducing more competitive pricing tiers. Ensure pricing reflects the value provided and explore bundling options to offer better perceived value.
By addressing these key areas, Databel can work towards reducing its churn rate and enhancing overall customer satisfaction and loyalty.


