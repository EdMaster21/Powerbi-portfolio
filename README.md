# Forecast vs Actual – Maintenance Cost Analysis

This project analyzes the variance between actual maintenance costs and forecasted values across wind farms.
The goal was to evaluate forecast accuracy and identify cost deviations across fiscal periods.

🚧 Problem

The dataset included multiple forecast versions reported monthly.
When visualized directly, Power BI aggregated them incorrectly, leading to misleading results.

💡 Solution
Designed a star schema data model
Separated Actuals vs Forecast into fact tables
Implemented forecast version control
Built DAX measures to correctly compare versions

📈 Key Insights
Forecasts tend to overestimate costs early in the year
Accuracy improves over time
Variance is driven by specific components

🛠 Tools & Skills
Power BI
Data Modeling (Star Schema)
DAX
Financial Analysis

📷 Dashboard Preview
<img width="2283" height="1285" alt="image" src="https://github.com/user-attachments/assets/d89235c3-d275-44c7-87ce-3550b90624b1" />

🎯 Key Technical Challenge

Handling multiple forecast versions without incorrect aggregation required careful control of filter context and data model design.
