🚧 PROJECT PAGE UNDER CONSTRUCTION 🚧  

# File Title: TITLE HERE  

**Superstore Returns Analysis**

**Project Overview**

This project aims to analyze the high number of returned orders at the Superstore. The objective is to identify key factors contributing to returns and develop a data-driven strategy to reduce return rates. The final deliverables will include an analysis report, an interactive Tableau dashboard, and a presentation for the CEO of the Superstore.

**Scope**

- Identify key drivers behind returned orders.
- Analyze the correlation between sales and returns.
- Evaluate return rates by product category, customer behavior, geographic location, and seasonal trends.
- Develop a Tableau dashboard for monitoring and mitigating return issues.
- Provide recommendations based on the analysis.
- Roles & Responsibilities
- Junior Analyst (You): Perform data analysis, create visualizations, and build the dashboard.
- Team Lead: Provide feedback on analysis, ensure project alignment, and approve deliverables.
- CEO (Stakeholder): Review insights and recommendations for business decisions. <br/><br/>


[<img src="https://github.com/Turner-Walz/Data_projects_TripleTen/blob/main/Superstore%20Returns/Snip%20of%20Project%20Dashboard" alt="First Sheet of Project**">](https://github.com/Turner-Walz/Data_projects_TripleTen/blob/main/Superstore%20Returns/Snip%20of%20Project%20Dashboard)  
[Project can be found here](https://public.tableau.com/app/profile/turner.walz/viz/Sprint5Project-StorytellingWithData/Story) <br/>
[Raw Data can be found here](https://1drv.ms/x/c/1ca507718247c69e/ESxe-eHrW0hGu_oJGe_8f7gBAUTrdZJTTf8i1YiuhixKDg?e=XIqBWH&nav=MTVfezg1QkZFNkVELTlCNEItNEE5Ny05Q0U0LTNEODEyRTEzNUZGNX0) <br/><br/>

### Table of Contents for Repository Artifacts
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [Superstore Returns](https://public.tableau.com/app/profile/turner.walz/viz/Sprint5Project-StorytellingWithData/Story) | A project that analyzes where the high number of returns are coming from for a retail store. |
| 2 | [Raw Data File](https://1drv.ms/x/c/1ca507718247c69e/ESxe-eHrW0hGu_oJGe_8f7gBAUTrdZJTTf8i1YiuhixKDg?e=XIqBWH&nav=MTVfezg1QkZFNkVELTlCNEItNEE5Ny05Q0U0LTNEODEyRTEzNUZGNX0) | The data that was imported into Tableau for analysis. |
| 3 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 4 | [Requirements.txt](https://github.com/Turner-Walz/Data_projects_TripleTen/blob/main/Superstore%20Returns/requirements.txt) | A simple .txt file with the provided project requirements as provided by TripleTen. |

### Table of Contents for README
| Section Title | Description |
| ----------- |----------- |
| [Description](LINK) | Describes the final product's purpose, software, format, and included visuals. |
| [Process](LINK) | Describes the process, including tools or tech used. |
| [Data](LINK) | Describes the data source, including files, tables, and fields. |
| [Assumptions](LINK) | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| [Findings](LINK) | Insights learned from the data analysis. |
| [Recommendations](LINK) | Recommended direction for the stakeholders based on the final analysis. |
| [Notes](LINK) | Lists any special requests from the reviews or stakeholders unique to this project. |

#### Description:
- This project aims to analyze the high number of returned orders at the Superstore. The objective is to identify key factors contributing to returns and develop a data-driven strategy to reduce return rates. The final deliverables will include an analysis report, an interactive Tableau dashboard, and a presentation for the CEO of the Superstore.

#### Process:

Data Preparation:
- Join the Returns table with the Orders table using a LEFT JOIN.
- Create a calculated field for returns (1 for returned orders, 0 for non-returned orders).
- Aggregate data by various dimensions (category, customer, geography, time 

#### Data
The analysis is based on the following datasets:
1️⃣ '`Orders'` Contains details of all purchases, including order ID, customer ID, product ID, sales amount, and order date.<br/>
2️⃣ '`Returns'` Specifies which orders were returned, linked by order ID.<br/>
3️⃣ '`Products'` Contains product information, including category and subcategory.<br/>
4️⃣ '`Customers'` Provides customer segmentation data.<br/>
5️⃣ '`Geography'` Includes location-based data to analyze return trends by region.<br/>

#### Assumptions:
- We only used the data that was given to us for this project along with the tools Excel and Tableau. 


#### Findings:
- The return rates can be tied to certain outlying customers having super high return rates, specific states returning more product than others, and specfici times of year that seem to lead to products getting returned more. 

#### Recommendations/Results:
- Conduct future studies diving into our high return areas to see what things specifically that could be changed to decrease overall returns. 


