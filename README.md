## LITA_CAPSTONE_CUSTOMER_SUBSCRIPTION_SERVICE
This is where i documented my second project while learning data analysis with the Incubator Hub.
### PROJECT TITLE:CUSTOMER SEGMENTATION FOR A SUBSCRIPTION SERVICE

PROJECT OVERVIEW
DATA SOURCES
TOOLS USED
DATA CLEANING AND PREPARATION
EXPLORATORY DATA ANALYSIS
DATA ANALYSIS
DATA VISUALIZATION
INSIGHTS ANALYSIS
 RECOMMENDATION
---
### PROJECT OVERVIEW
    This project involves analyzing customer data for a subscription service to identify segments and trends.
    It is done by analyzing data using Pivot table from Capstone Customer Dataset. Also, different queries 
    were executed from the database using SQL and thereafter,imported into PowerBI where the actual analysis 
    was carried out in order to understand customer behavior, track subscription types,and identify
    key trends in cancellations and renewals. 
---
### DATA SOURCES
    The Data used for this project work is gotten from LITA Incubator Hub.The primary source 
    of the Data is Data CSV and it is an open source Dataset that can be freely downloaded 
    from Kaggle or any other Data repository site.
 ---
### TOOLS USED
-Microsoft Excel :
  - For Data Cleaning
  - For Analyzing
  - For Data Visualization
- SQL : Structured Query Language for Querying of Data
- PowerBI:
  - For Data Modelling
  - For Data Visualization
  - Creating Key Performance Indicators(KPIs)
  - Using DAX Function to perform basic measures
- Github for portfolio building.
---
 ### DATA CLEANING AND PREPARATION
  In the initial of the Data cleaning and preparation, the following actions were performed;
   - Data loading and inspection
   - Using Excel function to calculate the Average Subscription Duration.
   - Data cleaning and formatting: Duplicate were removed from rows in Excel using the filter
function to search for those empty rows. Then, Remove Duplicate function is used to the remove duplicate.
---
###  EXPLORATORY DATA ANALYSIS
1. Excel:
  - Analyze customer data using pivot tables to find subscription patterns.
  - Calculate the average subscription duration and identify the most popular 
subscription types.
  -Create any other interesting reports.
2. SQL:Write queries to extract key insights based on the following questions. 
- retrieve the total number of customers from each region.
- find the most popular subscription type by the number of customers.
- find customers who canceled their subscription within 6 months.
- calculate the average subscription duration for all customers.
- find customers with subscriptions longer than 12 months.
- calculate total revenue by subscription type.
- find the top 3 regions by subscription cancellations.
- find the total number of active and canceled subscriptions.
3. Power BI: Build a Power BI dashboard that visualizes
- key customer segments, cancellations, and
- subscription trends.
- Include slicers for interactive analysis.
---
### DATA ANALYSIS
 This is where i used pivot tables to find the subscription patterns,Calculate the average subscription duration and identify the most popular 
subscription types. Other interesting reports were also created.
- Diagram of the pivot tables
- 
-  ![REGION BY SUBSCRIPTION TYPE WITH REVENUE](https://github.com/user-attachments/assets/5df6a4b6-e20b-4cdc-ac1e-f982ef53cd32)
  
-  ![Subscription Type By Average Subscription Duration](https://github.com/user-attachments/assets/9210f8e7-fa13-4b8a-be57-c9f1ff8504df)
  
- ![SUBSCRIPTION TYPE BY CANCELED WITH REVENUE](https://github.com/user-attachments/assets/48daf878-f446-4d69-9bf9-caac3700f40d)
 
-  ![CUSTOMERNAME BY CANCELED WITH REVENUE](https://github.com/user-attachments/assets/de9dc0a9-3248-4b05-98f5-1725f300c41e)
  
-  ![REGION BY CANCELED WITH REVENUE](https://github.com/user-attachments/assets/a70eaf46-d9ce-4e54-9135-79b1f6022d80)

 The Customer table was imported into SQL Management Studio were some queries were executed in order to get some ananlysis.

 - ![total customer by region](https://github.com/user-attachments/assets/e781e7c4-bf61-413a-b82b-a98eac49b4fb)
   
 - ![POPULAR SUBSCRIPTION TYPE](https://github.com/user-attachments/assets/b0e45d5d-2b1b-42bc-b848-efc8c9538db8)
   
 - ![CUSTOMER WHO CANCELED SUBCRIPTION](https://github.com/user-attachments/assets/d9f54ea0-96c6-43c4-97da-c3267e3cd1f4)
   
 - ![AVERAGE SUBSCRIPTIN DURATION](https://github.com/user-attachments/assets/c8a0baff-9342-4833-a87d-e5d1d46ab3b5)
   
 - ![CUSTOMER WITH SUBSCRIPTION ](https://github.com/user-attachments/assets/0f7c7399-de5b-4efa-91c7-e3e711a177ff)
   
 - ![TOP 3 REGION BY SUBSCRIPTION CANCELED](https://github.com/user-attachments/assets/a334b98c-215f-4a41-8963-cf79909a888f)
   
 - ![TOTAL REVENUE BY SUBSCRIPTIN TYPE](https://github.com/user-attachments/assets/b5cdd56b-b09b-4898-986d-b1a29f9cda7b)
   
 - ![NO OF ACTIVE AND CANCELED SUBSCRIPTION](https://github.com/user-attachments/assets/310de7f0-d065-4c7a-8a99-63316d01e022)

---
### DATA VISUALIZATION
 The table was then imported into PowerBI desktop for analysis.I transformed the Data in Power Query,checked for column qualit,
distribution, profile and Data types. DAX function was used to calculate conditional column in order to get the cancellation rate.
and measure was used to generate the average subscription type.Also Q&A Al visuals was used to generate some valves.
Several expressions and functions were made to arrive at a desired KPI or metrics. which are:
  - Customer Segments
  - Cancellation and
  - Subscription Trends

- ![CUSTOMER SEGMENTATION FOR A SUBSCRIPTION SERVICE ANALYSIS](https://github.com/user-attachments/assets/4184132e-6b74-47fb-8396-ed5f67b57510)

### INSIGHTS ANALYSIS
- The average subscription duration is 365 which is within a year which Basic happens to be the highest subscription type
  with total revenue of 34millions.
- The region that has the highest revenue is East with the total revenue of 17millions
- Premium and Standard have the highest number of cancellation.
---
### RECOMMENDATION
 I recommend that the region with the highest number of cancellation should be examined and also discount should be given
 to customers so as to increase the number of subscription users.
 
