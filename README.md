# PowerBi Project
This is a PowerBi Project for the company named Atliq in India
There is an SQL data file provided in this repository which is used to create the end result of the PowerBi Dashboard (.pbix file)

## Problem Statement :

  1. The market is growing dynamically and the sales team have a problem keeping track of their sales in this dynamically growing market. They are having issues with the insights of their business
  2. Whenever the sales director asks the company employees for the reduced sales, the answer is quite vague and he is not happy with the team's performance. He is also unable to figure out what products are selling or what are the highest grossing areas in India where the company is making sales
  3. There are loads of excel files with so many rows in it to keep track of data that it is almost impossible to judge the reason.
  4. Therefore, the sales director is interested in getting a simple, understandable and digestible insights about the company's business


## Requirements of the company :

A PowerBi dashboard to get insights about the sales and track record of sales by year , by areas, and by customer company's name so that data driven decisions can be made to help grow the company in sales

## Architecture and Project Planning

### AIMS Grid and Data discovery
AIMS Grid is a project management tool and it has four components to it:
  1. PURPOSE => To unlock sale insights that are not visible before for sales team decision support and automate them to reduced manual time spent in data gathering
  2. STAKEHOLDERS => Who all will be involved in this project. For example: Sales Director, Marketing Team, Customer Service Team, Data & Analytics Team, IT Department, etc..
  3. END RESULT => An automated dashboard providing quick and latest insights in order to support data driven decision making.
  4. SUCCESS CRITERIA => Dashboard(s) uncovering sales order insights with latest data available. Sales team be able to take better decisions and prove , for example, 10% cost savings of total spend. Sales analyst stop data gathering to save 20% of their business time and reinvest it to other value added activities

### Data Warehouse and Transformation
We will use MySQL Database for this project, which is provided to us by the company itself. We will take the data from the SQL through OLTP - Online Transaction Processing System - and do transformation which is called ETL - Ectract Transform and Load - and then data is stored in the data warehouse.

### Data Cleaning and Merging
Data cleaning will be done using PowerQuery using PowerBi and then data will be merged. 
In this case, one example of ETL will be to normalise currency to convert all separate currencies to INR - which will be normalised currency for the sales amount.

The end step will be to make a well-suited easy to control PowerBi Dashboard for the company and a mobile version is also created and uploaded on the workspace in the PowerBi cloud.

### Final Dashboard 

(Download available in pdf format)
[BasicDashboard.pdf](https://github.com/alokiksingh1/PowerBI_Proj/files/15299690/BasicDashboard.pdf)
<img width="1265" alt="PowerBI_BasicDashboard" src="https://github.com/alokiksingh1/PowerBI_Proj/assets/101609750/25c93ade-87f5-4685-8647-d225e7564a47">
