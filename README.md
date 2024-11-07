## LITA_CLASS_PROJECT_ASSIGNMENT
This is where I documented My Project Assignments on Capstone Customer Data for Incubator Hub

### Project Title: Capstone Consumer Data Analysis

### Project Overview
----
This Project involves analyzing customer data for a subscription service to identify segments and trends.The project leverages various tools to identify trends in customer subscription behavior, segment customers for targeted marketing and analyze revenue growth and customer lifetime value etc. This projects will help to optimize rentention and acquisition of customers and also generating revenue for the Company.

### Data Sources
----
The primary source dataset used here is "LITA Capstone Dataset_27027859 XLSX Worksheet (.xlsx)" and this is a source that was provided for by the Incubator Hub Data Analysis Instructors. The Dataset consists of 75,001 customer records with 8 variables, including CustomerID, CustomerNames, Region,Subscription Types and status.

### Tools Used
----
- Miscrosoft Excel [Download here](https://microsoft.com)
   1. Data Cleaning
   2. Analysis(Pivot Table)
   3. Visualization(Graph)
- SQL- Structured Query Language
   1. Running Queries
   2. Validating queries
- PowerBI
   1. Creating Dahsboard for visualizations for interactive Presentations
- Github for Portofolio Building

### Data Cleaning and Preparations
-----
We performed the forllowing tasks at this stage for the Data cleaning and Preparation;
   1. Data Loading and inspection
   2. Removal of Duplicates
   3. Dta Formatting
   4. Handling missing values
   5. checking column quality
   6. Tranform Data

### Exploratory Data Analysis
This involves the expoloring of the Data to examine and summarise the data to understand customer behaviour, prefernces and trends. The following questions were asked;
- Total number of customers in each region?
- Customers that have canceled or renewd their subscription
- which subscription plan is the most popular?
- What is the Average Subscription duration?

### Data Analysis
-----
- Pivot tables were used to analyse subscription patterns and identifying key segments.
- SQL queries were used to validate data and investigate specific trends;
```SQL
SELECT * FROM table1
select Region, count (*) as Numberofsalestransaction from [dbo].[SALESDATACAPSTONE]
Group by Region
```
- PowerBI was used to create interactive dashboards and visualize key findings.
  
### Data Visualization
![CAPSTONE PROJECT CUSTOMER DATA EXCEL](https://github.com/user-attachments/assets/fcc7c37e-e5f6-47b1-bf99-1cf97cc0ac12)

![CAPSTONE PROJECT CUSTOMER DATA PIVOT](https://github.com/user-attachments/assets/5a5b4841-48d0-4a26-9de3-db97582d72a2)

![CAPSTONE PROJECT CUSTOMER DATA SQL](https://github.com/user-attachments/assets/70542b31-70aa-48a1-84bb-bdb8503412e4)

![CAPSTONE PROJECT CUSTOMER DATA VISUALS](https://github.com/user-attachments/assets/2b513f50-3020-4988-9beb-c7c74e957372)


### Results/Findings
The summaries Results/findings are as follows;
1. The Basic plan is the most popular of the subscription type, 60% of customers subscribe to this plan, with an average duration of 6months.
2. Identified segments based on Location and subscription plan
3. The company presence has been steadliy increased over the past year in the East Region.
4. The number of customers that has canceled their subscription plans has drastically increased, which has affected the revenue growth of the company.

### Recommendations
Baseed on the analysis we recommend the following actions;
- Collaborate with marketing teams to create targeted campaigns based on identified customer segments and develop services tailored to identify customer needs.
- Focus on expanding and promoting produts in other Regions for wider reach.
- Develop a customer rention program based on the insight from the analysis





