# File Title: Superstore Returns Analysis  

### Table of Contents for Repository Artifacts
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [Superstore Returns](https://public.tableau.com/app/profile/turner.walz/viz/ProjectSuperstoreReturns/Story?publish=yes) | A project that analyzes where the high number of returns are coming from for a retail store. |
| 2 | [Raw Data File](https://1drv.ms/x/c/1ca507718247c69e/ESxe-eHrW0hGu_oJGe_8f7gBAUTrdZJTTf8i1YiuhixKDg?e=XIqBWH&nav=MTVfezg1QkZFNkVELTlCNEItNEE5Ny05Q0U0LTNEODEyRTEzNUZGNX0) | The data that was imported into Tableau for analysis. |
| 3 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 4 | [Requirements.txt](https://github.com/Turner-Walz/Data_projects_TripleTen/blob/main/Superstore%20Returns/requirements.txt) | A simple .txt file with the provided project requirements as provided by TripleTen. |

**Project Overview**

This project aims to analyze the high number of returned orders at the Superstore. The objective is to identify key factors contributing to returns and develop a data-driven strategy to reduce return rates. The final deliverables will include an analysis report, an interactive Tableau dashboard, and a presentation for the CEO of the Superstore.

**Scope**

- Identify key drivers behind returned orders.
- Analyze the correlation between sales and returns.
- Evaluate return rates by product category, customer behavior, geographic location, and seasonal trends.
- Develop a Tableau dashboard for monitoring and mitigating return issues.
- Provide recommendations based on the analysis.<br/>


[<img src="https://github.com/Turner-Walz/Data_projects_TripleTen/blob/main/Superstore%20Returns/Snip%20of%20Project%20Dashboard" alt="First Sheet of Project**">](https://github.com/Turner-Walz/Data_projects_TripleTen/blob/main/Superstore%20Returns/Snip%20of%20Project%20Dashboard)  
[Project here](https://public.tableau.com/app/profile/turner.walz/viz/ProjectSuperstoreReturns/Story?publish=yes) <br/>
[Raw Data here](https://1drv.ms/x/c/1ca507718247c69e/ESxe-eHrW0hGu_oJGe_8f7gBAUTrdZJTTf8i1YiuhixKDg?e=XIqBWH&nav=MTVfezg1QkZFNkVELTlCNEItNEE5Ny05Q0U0LTNEODEyRTEzNUZGNX0) <br/><br/>

#### Description:
- This project aims to analyze the high number of returned orders at the Superstore. The objective is to identify key factors contributing to returns and develop a data-driven strategy to reduce return rates. The final deliverables will include an analysis report, an interactive Tableau dashboard, and a presentation for the CEO of the Superstore.

#### Process:

Data Preparation:
- Join the Returns table with the Orders table using a LEFT JOIN.
- Create a calculated field for returns (1 for returned orders, 0 for non-returned orders).
- Aggregate data by various dimensions (category, customer, geography, time 

#### Data
The analysis is based on the following datasets:<br/>

'`Orders'` Contains details of all purchases, including order ID, customer ID, product ID, sales amount, and order date.<br/>

'`Returns'` Specifies which orders were returned, linked by order ID.<br/>

'`Products'` Contains product information, including category and subcategory.<br/>

'`Customers'` Provides customer segmentation data.<br/>

'`Geography'` Includes location-based data to analyze return trends by region.<br/>


#### Findings:
- The return rates can be tied to certain outlying customers having super high return rates, specific states returning more product than others, and specfici times of year that seem to lead to products getting returned more. 

#### Recommendations/Results:
- There are areas that have much higher returns that others. We found that certain customers had extremely high volumes of return, certain states were returning at a higher rate that others, and also there certain times of year where the increase in sales does not correlate with the amount of returns. From this we could conduct future analysis diving deeper into our high return areas to see what things specifically that could be changed to decrease overall returns. 


