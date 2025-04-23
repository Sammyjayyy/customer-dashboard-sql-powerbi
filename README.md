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
- The 26–35 age group demonstrates the highest spending tendencies.

## Tools Used

- PostgreSQL for data querying and cleaning
- Power BI for data visualization

## Download the Dashboard

https://github.com/Sammyjayyy/customer-dashboard-sql-powerbi/blob/main/customer%20behavior%20analysis.pbix

##Data Cleaning Steps##

The raw dataset was cleaned using Power BI Query Editor before analysis. Key steps included:
	•	Removed null values: Dropped records with missing Spending Score and Annual Income.
	•	Handled missing professions: Replaced nulls in Profession with "Unknown".
	•	Created new columns: Derived columns like Age Group, Income Level, and grouped Family Size.
	•	Standardized formatting: Ensured consistent data types across all fields.

⸻

##Recommendations##

Based on insights from the analysis, here are some strategic recommendations:
	•	Target Entertainment & Artist professions: These groups have high spending behavior.
	•	Focus on customers aged 18–25: This segment shows the highest average spending score.
	•	Promote to families of 3–5 members: These groups spend more than others.
	•	Investigate low spending in Upper-Mid income group: Could be untapped opportunity or data quality issue.

