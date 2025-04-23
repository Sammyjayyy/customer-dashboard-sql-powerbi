# Customer Spending Analysis Dashboard

This Power BI dashboard analyzes customer behavior using data processed in PostgreSQL. It offers insights into:

- Gender
- Age Group
- Income Level
- Profession
- Family Size

## Dashboard Preview

![image](https://github.com/user-attachments/assets/43c645c8-edf4-4c13-b05a-fa58d60db245)

## Key Insights

- Creative professionals exhibit the highest spending scores.
- Spending behavior is consistent across different income levels.
- The 18–25 age group demonstrates the highest spending tendencies.

## Tools Used

- PostgreSQL for data querying and cleaning
- Power BI for data visualization

## Download the Dashboard

https://github.com/Sammyjayyy/customer-dashboard-sql-powerbi/blob/main/customer%20behavior%20analysis.pbix

## Data Cleaning Steps

The raw dataset was cleaned using Power BI Query Editor before analysis. Key steps included:
- Removed null values: Dropped records with missing Spending Score and Annual Income.
- Handled missing professions: Replaced nulls in Profession with "Unknown".
- Created new columns: Derived columns like Age Group, Income Level, and grouped Family Size.
- Standardized formatting: Ensured consistent data types across all fields.



## Recommendations

Based on insights from the analysis, here are some strategic recommendations:

- Explore marketing campaigns targeted at creative professionals such as Artists and those in Entertainment, as they show the highest spending scores.
- Consider personalized strategies for the 36–44 age group, which has the lowest average spending score among all age brackets.
- Maintain a balanced approach across gender and income levels, since spending behavior appears consistent across both categories — this may suggest other non-demographic factors influence spending.
- Continue exploring behavioral or interest-based segmentation, as traditional demographics (like income and gender) alone may not fully explain spending patterns.
  
 ## Data Source

https://www.kaggle.com/datasets/datascientistanna/customers-dataset
 

