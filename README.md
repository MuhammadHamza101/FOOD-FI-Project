# FOOD-FI-Project
## Foodie-Fi Customer Subscription Analysis

This repository contains SQL queries and a detailed report for analyzing customer subscription data for Foodie-Fi, a subscription-based food service. 

**Key Features:**

* Analyzes customer acquisition, plan usage, churn rates, upgrade patterns, and downgrades.
* Provides insights to improve marketing strategies, optimize onboarding processes, and identify areas for customer retention.
* Includes clear and concise SQL queries with comments for easy understanding.
* Offers a comprehensive report template with explanations and placeholders for incorporating visualizations (charts, graphs).


**SQL Queries**

The `sql` folder contains the following SQL queries:

* `1_total_customers.sql`: Calculates the total number of distinct customers Foodie-Fi has ever had.
* `2_monthly_trial_signups.sql`: Analyzes the monthly distribution of trial plan signups.
* `3_plan_usage_after_2020.sql`: Investigates plan usage for subscriptions initiated after January 1st, 2021.
* `4_churn_rate.sql`: Calculates the customer churn rate (percentage of customers who canceled their subscription).
* `5_immediate_churn_after_trial.sql`: Explores how many customers churned immediately after their free trial.
* `6_next_plans_after_trial.sql`: Examines which paid plans customers typically choose after their free trial.
* `7_plan_breakdown_dec_31_2020.sql`: Analyzes the customer distribution across different plans on December 31st, 2020.
* `8_annual_plan_upgrades_2020.sql`: Determines how many customers upgraded to the annual plan in 2020.
* `9_average_upgrade_time.sql`: Calculates the average number of days it takes for a customer to upgrade to the annual plan.
* `10_upgrade_timeframe_breakdown.sql`: Breaks down the average upgrade time into 30-day periods.
* `11_downgrades_from_pro_monthly_2020.sql`: Investigates how many customers downgraded from the "pro monthly" plan to the basic monthly plan in 2020.

**Report Template**

The `foodie_fi_report.txt` file provides a framework for presenting the analysis in a clear and professional manner. It includes explanations for each section and placeholders for incorporating the SQL query results and visualizations.

**Contribution**

Feel free to fork this repository and contribute by adding new SQL queries or enhancing the report template.
