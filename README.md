# Customer Churn & Revenue Risk Analysis
## Identifying Operational Drivers of Customer Attrition
Analyzed 440k customer records to identify churn drivers, revenue exposure, and operational risk factors impacting customer retention in a subscription business.
Business Intelligence and Operations Analytics project focused on customer churn, revenue analytics, and predictive modeling.
—-
Executive Summary (Slides)
Download the presentation:
View Slides

## Business Problem
Customer churn represents a major challenge for subscription-based businesses.
High churn rates can significantly impact revenue stability, customer lifetime value, and long-term growth.
This project analyzes a subscription platform dataset to understand:
which customer segments are most likely to churn
what behavioral factors are associated with churn
how churn affects revenue generation
which operational signals may help predict customer attrition
The goal is to identify actionable insights that can help reduce churn and improve revenue stability. The analysis also supports customer retention strategies through predictive analytics and operational insights.

## Dataset
The dataset contains 440,832 customer records with behavioral, financial, and subscription-related variables.

Key variables include:
Age
Tenure
Usage Frequency
Support Calls
Payment Delay
Subscription Type
Contract Length
Total Spend
Churn
Note: The dataset used in this project is synthetic and designed for analytical practice.

## Analytical Approach
The analysis followed a structured workflow:
1 Data Exploration and Cleaning
dataset validation
missing value inspection
data type corrections
duplicate verification
2 Customer Segmentation Analysis
Examined churn behavior across:
subscription tiers
contract lengths
customer tenure
3 Revenue Analysis
Measured revenue dynamics across segments:
revenue by subscription type
revenue by contract structure
revenue distribution by churn status
revenue at risk due to churn
4 Risk Factor Analysis
Behavioral drivers of churn were evaluated using:
Support Calls
Payment Delay
Usage Frequency
Last Interaction
A Random Forest model was used as part of a predictive analytics approach to estimate feature importance and identify key churn drivers.

## Key Findings
Several insights emerged from the analysis.
1. Contract structure strongly influences churn
Customers with monthly contracts exhibit significantly higher churn rates compared with quarterly and annual contracts.
2. Revenue is primarily driven by customer volume
Average revenue per customer remains similar across subscription tiers, suggesting that overall revenue growth depends largely on customer base size rather than spending differences across plans.
3. Longer contracts generate the majority of revenue
Quarterly and annual contracts each generate approximately $115M in revenue, compared with about $48M from monthly contracts.
4. Customer churn exposes a significant portion of revenue
Approximately 48.6% of total revenue is associated with customers who eventually churn, highlighting substantial financial risk.
5. Operational friction is the strongest churn driver
Feature importance analysis indicates that Support Calls account for nearly half of the predictive importance, suggesting that service-related issues may be a major contributor to churn.

## Strategic Recommendations
Based on the findings, several opportunities emerge:
Investigate customer support interactions to identify recurring issues driving churn
Develop early-warning indicators based on support activity and payment delays
Encourage migration from monthly to longer-term contracts through incentives or pricing strategies
Improve customer support processes to reduce service-related friction
These actions aim to improve customer retention and reduce revenue risk through data-driven operational strategies.

## Tools Used
Python
Pandas
DuckDB
Scikit-learn
Seaborn
Jupyter Notebook
