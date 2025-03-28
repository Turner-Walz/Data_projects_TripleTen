# File Title: Vacation Rental Analysis 

### Table of Contents for Repository Artifacts
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [Vacation Rental Project](https://github.com/Turner-Walz/Data_projects_TripleTen/blob/main/Vacation%20Rental/Project%20Vacation%20Rental.xlsx) | The final project report for the rental analysis. |
| 2 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 3 | [Requirements.txt](https://github.com/Turner-Walz/Data_projects_TripleTen/blob/main/Vacation%20Rental/requirements.txt) | A simple .txt file with the provided project requirements as provided by TripleTen. |

**Overview** <br>
- This project analyzed Airbnb data to help a client identify the best neighborhoods and property sizes for vacation rentals in Manhattan. The goal was to determine the most attractive listings and calculate their revenue potential.

**Project Scope**

* Cleaned raw data by standardizing neighborhood names and handling missing values.
* Used Excel to create pivot tables and identify top neighborhoods and property sizes based on reviews.
* Calculated revenue for listings using IF() and SUMIF() functions, projecting annual earnings.
* Visualized key insights with charts and maintained clear, consistent formatting.
* Documented all steps in a change log and summarized findings with actionable recommendations.

**Deliverables**
* A cleaned and organized dataset, pivot table analysis, revenue projections, and a user-friendly spreadsheet with an executive summary.



![image](https://github.com/user-attachments/assets/9faca6da-6241-45b8-b290-b75cd9bd8574)
[Vacation Rental Project](https://docs.google.com/spreadsheets/d/1eOnkKUNXniFtqBsbZL4CgI8m0pCe-pKpNSIYBp_0Lww/edit?usp=sharing)


#### Description:
- This project format was in excel and has nine sheets in total. It also includes organizational tabs, raw data (Hidden), processed data, data analysis, pivot tables, and bar charts. We were able to draw insights backed by concrete data showing which areas performed the best and where a client could invest their money. 

#### Process:
1) **Data Preparation**: Filtering techniques were used to identify and clean inconsistencies within the Airbnb data. Irrelevant columns were hidden to maintain a focused analysis. Key functions such as PROPER, TRIM, IF, ISNUMBER, FIND, ROUND, SUMIF, VLOOKUP, CHOOSE, and WEEKDAY were employed for data tidying.
2) **Neighborhood Analysis**: Identify the top-performing neighborhoods based on review frequency via *Pivot Table*.
3) **Property Size Analysis**: Determine the optimal property sizes for each neighborhoodvia *Pivot Table* showcased with *conditional formatting*.
4) **Revenue Analysis**: Calculate estimated annual revenue for the most attractive listings.
5) **Additional Optional Analysis**: Perform Analysis through *Pivot Tables* for occupancy rates by day, price by super host status, check-in ratings by use of doormen, and price by review ratings.
6) **Data Visualization**: Create clear and informative *visualizations* (charts) to present findings.
7) **Formatting and Organization**: Ensure your analysis is well-formatted for ease of readability.
8) **Documentation**: Create organizational sheets like an executive summary, table of contents, assumptions log, and change log.

#### Data
The data was a Google spreadsheet file provided by TripleTen.<br>

`'nyc_airbnb_data.csv'`: each row corresponds to one listing on Airbnb in September 2022<br>

`'data_dictionary'`: summary of field titles seen in the file and its data type<br>

`'listings'`: uniquely listings available with all available data<br>

`'calendar'`: listings with upcoming availabilities and date-type data<br>

#### Assumptions:
- Data only reflects a one month period in the year 2022 from September 7th to October 6th. Other months were not considered.
- To generate the occupency of a listing, we assume 1 review from a client = 1 stay at a Airbnb property for data that was taken over the last 12 months. 


#### Findings:
- The three most attractive neighborhoods were Lower East Side, Hells Kitchen, and Harlem.
- The 3 most popular property sizes by number of bedrooms were studios, single bedrooms, and 2 bedrooms.
- The listing ID 49946551 was the top-earning listing as seen on pivot table name: Top Revenue by Listing Pivot Table.

