# Customer Shopping Behavior Analysis
I analyzed 3,900 customer purchases to uncover spending patterns and behavioral insights. I used Python for data cleaning and feature engineering, then integrated the dataset into PostgreSQL for structured SQL analysis on revenue and demographics. Finally, I built an interactive Power BI dashboard to visualize key metrics and provide data-driven business recommendations.
## Overview
The goal of this project was to uncover insights into spending patterns, customer segments, product preferences, and subscription behavior to guide strategic business decisions. I managed the entire data lifecycle—from raw data cleaning to final visualization and reporting

## Dataset
Rows: 3,900.\
Columns: 18.\
Key Features: Customer demographics (Age, Gender, Location), Purchase details (Category, Amount, Season), and Shopping behavior (Review Ratings, Subscription Status, Shipping Type).

## Tools Used
Data Cleaning: Python (Pandas)\
Database: PostgreSQL\
Visualization: Power BI\
Presentation: Gamma AI (PPT generation) and Microsoft Word (Reporting).

## Project Steps 
### EDA & Cleaning (Python): 
Handled 37 missing values in the Review Rating column by using category medians. \
Standardized columns to snake case and dropped redundant features like promo_code_used. \
Engineered new features including age_group and purchase_frequency_days. 
### SQL Analysis: Migrated the cleaned data to PostgreSQL for structured business queries. 
Calculated total revenue by gender and identified high-spending discount users. \
Segmented customers into New, Returning, and Loyal based on purchase history. 
### Visualization (Power BI): 
Developed an interactive dashboard to track an average purchase amount of $59.76 and a 3.75 average rating. \
Analyzed revenue contributions across different age groups and product categories. 
### Reporting: Used Gamma AI to create a professional presentation and documented all findings in a comprehensive report. 

## Key Results
Revenue: Male customers contributed $157,890 in revenue, while females contributed $75,191. \
Subscriptions: Approximately 27% of customers have a "Yes" subscription status. \
Top Products: Gloves, Sandals, and Boots emerged as the highest-rated items. \
Loyalty: Identified a significant "Loyal" segment consisting of 3,116 customers.

## How to Run
Exploratory Data Analysis: Open and run the my_portfolio_project_PY-JNB.ipynb notebook to view the data cleaning and feature engineering process. \
Database Analysis: Execute the queries in CBA-PostgreSQL.sql within your PostgreSQL environment to perform customer segmentation. \
Business Problem: Review BUSINESS PROBLEM STATEMENT.docx for the project objectives. \
Visualization: Open Customer_Behaviour_Dashboard.pbix in Power BI Desktop to interact with the visual insights. \
Final Report: Refer to Customer Shopping Behavior Analysis.docx for the full summary and business recommendations.
