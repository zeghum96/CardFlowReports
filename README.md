# Credit Card Weekly Status Report Dashboard
## Project Objective
The goal of this project is to develop a comprehensive Power BI dashboard for weekly status reporting of credit card operations. This dashboard will provide real-time insights into key performance metrics and trends, enabling stakeholders to effectively monitor and analyze credit card activities.

##  Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
Microsoft Power BI SQL Server (or any SQL database) Basic understanding of DAX queries
### Installation
1. #### Prepare your environment: Ensure that Power BI and SQL Server are installed and running on your machine.
2. #### Database Setup:
    *  Create tables in SQL as per the schema provided.
    * Import your CSV data into the SQL database using the provided scripts.
3. #### Power BI Setup:
    *  Open Power BI and connect to your SQL database.
    *  Import the tables into Power BI for creating visualizations.
## Dashboard Components
### Import Data to SQL Database
Steps to prepare and import data:

1. Prepare CSV file with the necessary columns.
2. Create tables in SQL using the provided SQL scripts.
3. Import the CSV file into the SQL database.
### DAX Queries
The dashboard utilizes several DAX queries to calculate metrics such as AgeGroup, IncomeGroup, and Revenue. These include:

* AgeGroup calculation based on customer age.
* IncomeGroup classification based on annual income.
* Revenue calculations for current and previous weeks.

### Project Insights- Week 53 (31st Dec)
#### WoW change:
* Revenue increased by 28.8%,
* Total Transaction Amt increased by 35%
* Customer count increased by 1.9%
#### Overview YTD:
* Overall revenue is 57M
* Total interest is 8M
* Total transaction amount is 46M
* Male customers are contributing more in revenue 31M, female 26M
* Blue & Silver credit card are contributing to 93% of overall transactions
* TX, NY & CA are contributing to 68%
* Overall Activation rate is 57.5%
* Overall Delinquent rate is 6.06%.
