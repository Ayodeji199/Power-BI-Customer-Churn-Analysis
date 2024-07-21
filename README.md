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

#### Overview

![image](https://github.com/user-attachments/assets/15759c68-c09f-4539-bbbc-cef301747229)

The dashboard provides a comprehensive overview of customer churn analysis for Databel, presenting key metrics and visualizations that reveal patterns and potential areas for improvement. Here is a detailed analysis and insights generated from the dashboard:

- Key Metrics:

Total Number of Customers: 6,687

This is the total customer base being analyzed.

 - Churn Rate: 26.86%

This indicates that approximately 27% of the customers have left the service. A churn rate close to 27% is relatively high and suggests significant issues with customer retention.

 - Number of Churned Customers: 1,796

Out of the total customer base, 1,796 customers have churned.

 - Churn Reasons:
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

 - Customer Segmentation by Contract Type:

Month to Month (62.87%): The majority of customers are on flexible contracts, which might make them more susceptible to churn.

Two Year (22.14%): A smaller segment, potentially indicating more stable customers.

One Year (14.98%): The smallest group, but still significant.

 - Geographic Distribution of Churn:

The map shows that churn is spread across the United States, with varying densities.

Higher Churn Areas: Larger green dots indicate regions with higher churn rates, often correlating with more populous areas.

Insights: Regions with higher churn may require tailored retention strategies, considering local competition and market conditions.

#### Age Group

![image](https://github.com/user-attachments/assets/448b23a1-768e-41ab-900f-19e0eae09a7c)

The dashboard provides a detailed analysis of customer churn segmented by age and average monthly charge. Here’s an in-depth look at the insights and implications derived from the dashboard:

 - Number of Customers and Churn Rate by Age
Left Chart:

 - Age Distribution: The chart shows the number of customers (blue bars) and the churn rate (dotted line) across different age groups (bins).

Key Observations:

Young Customers (20-30): This age group has a moderate number of customers with a relatively stable churn rate.

Middle Age Groups (30-50): These age groups represent the highest number of customers. However, the churn rate varies, showing a spike around the mid-40s.

Older Age Groups (50-70+): The number of customers decreases with age, but the churn rate significantly increases, especially after 60.

Insight: The highest churn rates are observed in the older age groups (60+), despite having fewer customers. Conversely, younger and middle-aged groups have higher customer numbers but relatively lower churn rates.

 - Average Monthly Charge and Churn Rate by Number of Customers in Group
Right Chart:

 - Monthly Charge vs. Churn Rate:

Low to Moderate Charges: Groups with lower average monthly charges have the highest number of customers but also exhibit a higher churn rate.

High Charges: As the average monthly charge increases, the number of customers decreases, but these groups tend to have lower churn rates.

Churn Rate Trends: There is a clear negative correlation between the average monthly charge and the churn rate. Higher charges are associated with lower churn rates.

Insight: Customers paying higher monthly charges are less likely to churn, indicating that higher-value customers are more satisfied or more committed to the service.

 - Combined Insights and Recommendations:

 - Target High-Churn Age Groups:

Insight: Older customers (60+) exhibit higher churn rates.

Recommendation: Develop targeted retention strategies for older age groups. This could include personalized support, loyalty programs, or services tailored to meet the needs of older customers.

 - Value Proposition for Middle-Aged Customers:

Insight: Middle-aged customers form the bulk of the customer base but show varying churn rates.

Recommendation: Enhance value propositions for middle-aged customers, such as bundling services, offering family plans, or providing additional benefits to ensure they remain engaged and satisfied.

 - Pricing Strategy:

Insight: Higher average monthly charges correlate with lower churn rates.

Recommendation: Consider revising pricing strategies to add more value to higher-tier plans. Promote these plans to potential high-value customers and provide incentives for existing customers to upgrade.

 - Customer Engagement and Support:

Insight: Customer satisfaction appears to be linked to lower churn rates in higher-paying groups.

Recommendation: Improve customer engagement and support services across all groups, with particular emphasis on personalized and premium support for higher-paying customers.

 - Focused Retention Programs:

Insight: The churn rate is relatively high for groups with low to moderate charges.

Recommendation: Implement focused retention programs for low and moderate-paying customers. These could include regular check-ins, feedback loops, and addressing specific pain points that may be causing dissatisfaction.

 - Age-Specific Marketing:

Insight: Different age groups exhibit different churn behaviors.

Recommendation: Tailor marketing campaigns to address the specific needs and preferences of different age groups. For instance, younger customers may value innovative features and flexibility, while older customers might prioritize reliability and customer support.

#### Payment and Contract

![image](https://github.com/user-attachments/assets/4226ca7e-ccc5-4977-9f63-4c6e8cbaff53)

The dashboard provides a comprehensive analysis of customer service calls and churn rates based on account length, payment methods, and contract categories. Here's a detailed analysis and insights derived from the dashboard:

##### Overview of Customer Service Calls
 - Sum of Customer Service Calls: 6,123
  
 - Average Customer Service Calls per Customer: 0.92

###### Churn Rate by Account Length, Payment Method, and Contract Category
Right Chart:

 - X-Axis: Average of Account Length (in months)
 - Y-Axis: Churn Rate
 - Contract Categories: Monthly and Yearly
 -  Data Points: Different combinations of payment methods and contract categories

 ###### Key Observations and Insights:
1. Contract Category and Churn Rate:

Monthly Contracts:
- Monthly contracts exhibit a higher churn rate overall.
- There is a data point with an account length of around 10 months showing a churn rate close to 60%.
- Other data points for monthly contracts also show relatively high churn rates compared to yearly contracts.

Yearly Contracts:
- Yearly contracts have significantly lower churn rates.
- Data points with account lengths around 20, 30, and 50 months show churn rates well below 20%, with some close to 0%.
- This indicates that customers with yearly contracts are more likely to stay longer with the company.

2. Account Length and Churn Rate:

- Shorter Account Lengths: Higher churn rates are more common in customers with shorter account lengths.
- Longer Account Lengths: As account length increases, churn rates tend to decrease.
- The data point with an account length of around 50 months shows the lowest churn rate, suggesting that longer-tenured customers are more loyal.

3. Payment Methods and Churn Rate:

- Direct Debit and Paper Check (Yearly): These payment methods in yearly contracts seem to correlate with lower churn rates.
- Credit Card (Monthly): Higher churn rates are associated with monthly credit card payments, indicating that customers on monthly plans who pay by credit card are more likely to churn.

##### Detailed Insights:

1. Customer Retention through Contract Terms:

- Insight: Yearly contracts are highly effective in reducing churn rates.
- Recommendation: Encourage customers to switch to yearly contracts through incentives such as discounts, additional services, or loyalty rewards.

2. Account Longevity and Customer Loyalty:

- Insight: Longer account lengths are associated with lower churn rates.
- Recommendation: Implement strategies to increase account longevity, such as personalized customer service, regular engagement, and value-added services that enhance customer satisfaction over time.

3. Payment Method Optimization:

- Insight: Payment methods impact churn rates, with direct debit and paper checks in yearly contracts showing lower churn rates.
- Recommendation: Promote direct debit and yearly payment options to customers, perhaps through special offers or highlighting the convenience and benefits of these methods.

4. Customer Service Efficiency:

- Insight: With 6,123 customer service calls and an average of 0.92 calls per customer, customer service interactions are a crucial touchpoint.
- Recommendation: Analyze the nature of these service calls to identify common issues and improve the efficiency and effectiveness of customer service. Reducing the need for repeated calls can enhance customer satisfaction and potentially reduce churn.

#### Extra Charges

![image](https://github.com/user-attachments/assets/964d1f63-c7ea-4fea-baf2-b10b887ce543)

##### Churn Rate by Unlimited Data Plan and Grouped Consumption

1. Unlimited Data Plan (Yes):
- Customers with 10 or more GB usage show a higher churn rate compared to those with less consumption.
- Churn rates for customers using between 5 and 10 GB and less than 5 GB are lower but still significant, indicating a potential dissatisfaction even with the unlimited plan.

2. Unlimited Data Plan (No):
- Customers using less than 5 GB have the lowest churn rate among all categories.
- Churn rates for customers using between 5 and 10 GB and 10 or more GB are similar and slightly higher compared to those on an unlimited plan.

##### Average Extra Charges
Right Panel Analysis:

- Average Extra International Charges: 33.64

- Average Extra Data Charges: 3.37

##### Key Observations and Insights:

1. Impact of Unlimited Data Plans on Churn Rate:

- High Consumption (10 or more GB):

 - Customers with unlimited data plans and high consumption (10 or more GB) still exhibit a notable churn rate. This suggests that simply offering unlimited data is not sufficient to retain high-usage customers.
 
 - Insight: High consumption customers may be seeking better value, additional features, or superior service quality beyond just unlimited data.

- Moderate to Low Consumption (Less than 10 GB):

 - Churn rates for these customers are generally lower, indicating moderate satisfaction with the plan.

2. Impact of Not Having Unlimited Data Plans:

- Low Consumption (Less than 5 GB):

 - These customers have the lowest churn rate, suggesting they may find their current data plan adequate and are not experiencing overage charges or data restrictions.
- Moderate to High Consumption (5 GB or more):
 - Higher churn rates in these categories indicate dissatisfaction potentially due to overage charges or limited data allowances.

3. Average Extra Charges Analysis:

- High International Charges:
With an average of 33.64 in extra international charges, customers making frequent international calls might be experiencing bill shock, contributing to churn.
 - Insight: Reducing or offering bundled international call plans could help retain these customers.

- Low Extra Data Charges:
The average extra data charges are relatively low (3.37), indicating that data overage charges may not be a primary concern for most customers. This suggests that other factors like service quality or plan features might be driving churn.

### Conclusion and Recommendations

#### Conclusion

The comprehensive analysis of Databel's customer churn using Power BI reveals several critical insights and patterns. The overall churn rate is alarmingly high at approximately 27%, indicating significant retention challenges. Key factors contributing to churn include competitive offers, customer service issues, and dissatisfaction with product or pricing. Additionally, various customer segments, such as older age groups and those on monthly contracts, exhibit higher churn rates. The analysis also highlights the impact of unlimited data plans, payment methods, and extra charges on customer retention.

#### Recommendations

1. Enhanced Competitor Analysis and Competitive Offers:

- Insight: The primary reason for churn is competitors offering better deals.

- Recommendation: Regularly monitor competitors' offerings and adjust pricing or package features to ensure competitive value. Introduce loyalty programs or exclusive benefits for long-term customers to enhance perceived value.

2. Customer Service Improvement:

- Insight: A significant number of customers churn due to poor support experiences.

- Recommendation: Invest in customer service training and implement feedback loops to continually improve service quality. Consider offering premium support for high-value customers and ensuring faster resolution times.

3. Targeted Retention Strategies for High-Churn Segments:

- Older Customers (60+): Implement personalized support, loyalty programs, and senior-friendly services to cater to their specific needs.

- High Usage Customers: For customers using 10 or more GB, focus on providing additional features, superior network performance, and bundled services that go beyond just unlimited data.

4. Contract Optimization:

- Insight: Yearly contracts have significantly lower churn rates compared to monthly contracts.

- Recommendation: Encourage customers to switch to longer-term contracts by offering discounts, additional benefits, or enhanced services. Highlight the cost savings and additional value of yearly contracts in marketing communications.

5. Data-Driven Marketing Campaigns:

- Insight: Different age groups exhibit varying churn behaviors.
- Recommendation: Develop age-specific marketing campaigns. For younger customers, emphasize innovative features and flexibility. For middle-aged and older customers, focus on reliability, customer support, and value-added services.

6. Payment Method Promotion:

- Insight: Direct debit and yearly payment methods are associated with lower churn rates.
- Recommendation: Promote direct debit and yearly payment options through incentives such as discounts or added benefits. Highlight the convenience and security of these payment methods in communications.

By implementing these recommendations, Databel can better understand customer needs, enhance service offerings, and reduce churn rates, ultimately improving customer retention and satisfaction.
