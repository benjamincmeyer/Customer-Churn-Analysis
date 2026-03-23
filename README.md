## Customer-Churn-Analysis
This project analyzes customer churn behavior for a fictitious telecom company to identify high-risk customer segments and recommend data-driven retention strategies.

The goal of this analysis was to answer:
- What factors are driving customer churn?
- What segments of customers are most at risk of leaving?
- What actions might reduce churn and improve retention?

# Key Insights
- Overall churn rate is ~26.5%, indicating a significant retention challenge.
- Customers on month-to-month contracts have the highest churn rates (~42.7%).
- New customers (0–10 months tenure) are significantly more likely to churn, suggesting onboarding and early experience issues.
- Customers without tech support churn at much higher rates (~41.6%) compared to those with support (~15.2%).
- Fiber optic customers show higher churn (~41.9%), likely due to higher costs or unmet expectations.

# High Risk Segment
- Month-to-month contracts
- 0–10 months tenure
- Fiber optic internet
- No tech support

This group had ~72% churn rate, nearly 3x the overall rate of 26.5%

# Dashboard
The interactive dashboard includes:
 - KPI Summary (total customers, churn rate, etc.)
 - Churn breakdown by Tech Support, Contract Type, Internet Service Type, Tenure Group
 - High Risk Flag Segment
 - Filters for dynamic exploration

# Tools Used
- Tableau (data visualization via dashboard)
- Excel (data cleaning/formatting)

# Data Used
- Telco-Customer-Churn.csv
- https://github.com/IBM/telco-customer-churn-on-icp4d/tree/d5371f5d83a446ad5673cbcca3b814b926491f8a/data

# Business Recommendations
Based on the analysis, the following actions are recommended:
- Improve on-boarding and incentives for new customers (first 10 months)
- Invest in Tech Support availability for all customers (esp. Fiber, Month-to-month contracts)
- Target high-risk customer segments early with retention campaigns

# Project Value
The project demonstrates aptitude in creating: 
- Customer segmentation and churn analysis
- KPI development and dashboard design
- Business insight generation and communication
- Data-driven decision support
