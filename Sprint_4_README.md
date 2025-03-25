# File Title: Superstore Data Analysis Project

**DESCRIPTION OF PROJECT SCOPE, ROLES, & RESPONSIBILITIES**

This project analyzes the Superstore sales data to identify key areas for profit improvement, assess the potential impact of advertising campaigns, and investigate the root causes of product returns.

Link to project here: https://public.tableau.com/app/profile/eddy.sanchez8351/viz/Book1_17348450252030/AvgReturnRatevsAvgProfitbyState

### Table of Contents for README

| Section Title | Description |
|---|---|
| Description | Describes the final product's purpose, software, and included visuals. |
| Process | Describes the process, including tools or tech used. |
| Data | Describes the data source, including files, tables, and fields. |
| Assumptions | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| Findings | Insights learned from the data analysis. |

#### Description:

* **SOFTWARE:** Tableau Public
* **NUMBER OF SHEETS:** (Number of sheets in your Tableau workbook)
* **DESCRIPTION OF WHAT'S INCLUDED/ANALYTICAL FORMATS HERE:** This project utilizes interactive dashboards to visualize key findings from the Superstore sales data. The analysis focuses on identifying profitable product categories, assessing the potential impact of advertising campaigns, and investigating the root causes of product returns.

#### Process:

* **DATA CLEANING AND PREPARATION:** The Superstore dataset was imported into Tableau Public. Data cleaning and preparation steps include handling missing values, formatting data types, and creating calculated fields (e.g., return rate).
* **DATA ANALYSIS AND VISUALIZATION:** Various chart types were used to visualize the data, including bar charts, scatter plots, and maps. Interactive filters and dashboards were created to allow for dynamic exploration of the data.
* **INSIGHT GENERATION AND STORYTELLING:** Key findings were identified and presented in a clear and concise manner through data visualizations and accompanying narratives.

#### Data

* **DESCRIPTION:** The Superstore dataset includes information on sales orders, products, customers, and returns.
    * **'Orders' Table:** Contains information about each order, including order ID, customer ID, order date, ship date, ship mode, customer name, segment, city, state, country, region, product ID, category, subcategory, product name, sales, quantity, discount, profit.
    * **'Returns' Table:** Contains information about returned orders, including order ID, returned.

#### Assumptions

* Left Join of Returns Table:

If: We assume the Returns table is left-joined onto the Orders table correctly,
Then: We will be able to identify both "Yes" and "null" values in the "Returned" column, which is crucial for accurately calculating return rates.

* Calculated Return Field:

If: We assume the calculated field for "Returned" is created correctly, assigning "0" to null values and "1" to "Yes" values,
Then: We can use this field to accurately calculate return rates for products and customers, leading to the identification of products and customers with the highest return rates.

* Advertising Cost Estimation:

If: We assume a willingness to spend 1/5 of profits on advertising for this exercise,
Then: We can estimate a budget for advertising campaigns based on the Superstore's average profit per unit sold, which can then be used to prioritize advertising efforts in the top 3 states/month combinations.

#### Findings

* **Profit Centers and Loss-Makers:**
    * **Profit Centers:** 
        * West Region: $162,494.22 total profit
        * California: $116,475.32 total profit
    * **Loss-Makers:** 
        * Central Region: Highest total profit loss
        * Texas: $-45,683.17 total profit loss
* **Products to Discontinue:**
    * Any product with negative profit should be discontinued. 
* **Product Subcategories:**
    * **Focus On:** Copiers, Phones, Accessories
    * **Discontinue:** Tables, Bookcases, Supplies
* **Advertising Opportunities:**
    * **Top 3 Combinations:**
        * Indiana & October 
        * Vermont & November
        * Washington & March
* **Product Return Rates:**
    * Identified products and customers with the highest return rates. 
* **State Profitability:**
    * States with negative profit should be improved or discontinued.
    * States with positive profit should be continued with more focus.


#### Notes:

* This analysis provides a high-level overview of the Superstore's sales performance. 

