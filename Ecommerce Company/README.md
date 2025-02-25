# File Title: ECommmerce Company  

### Table of Contents for Repository Artifacts
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [ECommerce Company Analysis Project](https://github.com/Turner-Walz/Data_projects_TripleTen/blob/main/Ecommerce%20Company/Project%20Ecommerce%20Company.xlsx)  | The task for this project was to process raw event logs and build a conversion funnel in order to conduct a cohort analysis. |
| 2 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 3 | [Requirements.txt](https://github.com/Turner-Walz/Data_projects_TripleTen/blob/main/Ecommerce%20Company/requirements.txt) | A simple .txt file with the provided project requirements as provided by TripleTen. |

**Project Overview**

As a junior analyst at an e-commerce company, your primary task is to analyze raw transaction logs and turn them into actionable business insights. The executive team seeks to understand user behavior on the website, focusing on conversion rates and retention metrics. This project involves processing raw event logs, building a conversion funnel, conducting cohort analysis, and presenting findings in an organized, executive-friendly manner.

**Project Scope**

- Objective: Analyze user activity data to generate key business metrics, including conversion rates and retention rates.

- Tools Used: Google Sheets (Excel equivalent), pivot tables, formulas (VLOOKUP, TEXT, DATEDIF, etc.).

- Deliverables: Conversion funnel analysis, cohort retention analysis, executive summary, and a well-documented spreadsheet.


[<img src="https://github.com/Turner-Walz/Data_projects_TripleTen/blob/main/Ecommerce%20Company/Snip%20of%20Table%20of%20Contents%20Page" alt="First Sheet of Project**">](https://github.com/Turner-Walz/Data_projects_TripleTen/blob/main/Ecommerce%20Company/Snip%20of%20Table%20of%20Contents%20Page)  

[E Commerce Company Analysis Project](https://github.com/Turner-Walz/Data_projects_TripleTen/blob/main/Ecommerce%20Company/Project%20Ecommerce%20Company.xlsx) 

#### Data

The dataset contains user activity logs with the following attributes:
`'user_id'` - Unique identifier for each customer.

`'event_type'` - Type of activity (e.g., page view, cart open, purchase).

`'category_code'` - Product category viewed or purchased.

`'brand'` - Brand of the product.

`'price'` - Price of the product in USD.

`'event_date'` - Date of user activity in YYYY-MM-DD format.

#### Description:
- This project provides deep insights into how users interact with the e-commerce website. The conversion funnel helps assess how efficiently users move through the purchase process, while the cohort analysis identifies customer retention patterns. By structuring the analysis in a clear, professional manner, this project enables the executive team to make informed, data-driven decisions.

#### Findings:
- The company is converting 1 in 10 customers to buyers. An important takeaway here is that 35% of people that put an item in their cart are going to make the purchase. Focusing on getting people to put things in their shopping cart could improve sales overall and increase the overall conversion rate. We analyzed the unique user counts within each event type from Raw User Activity to get these numbers.
- Cohorts were formed by the month a customer made their first purchase. In September of 2020 they had their highest rate of retention after their first month, and taking a look at what the company did to retain customers during this month could give us an idea of what to try to get higher retention. Each cohort was tracked month over month (cohort age) to see what sort of buying activity they had. The rates were calculated by dividing the total number that bought a product in the subsequent months by the original amount of customers that were in the cohort. 



