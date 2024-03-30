 # InsuranceClaimsAnalysis_python

# Insurance Claims Analysis

## Introduction

This repository contains a data analysis project focused on insurance claims data. The project involves importing and combining datasets, performing data audits, data cleaning, feature engineering, and conducting various analyses to derive insights from the data.

## Dataset Description

The dataset includes two main files: `claims_data.csv` and `cust_data.csv`. These files contain information about insurance claims and customer details respectively. 

## List of Tasks

### 1. Import and Combine Datasets
- Import `claims_data.csv` and `cust_data.csv`.
- Combine the two datasets appropriately to create a comprehensive view of the data.

### 2. Data Audit
- Perform a data audit to check for any discrepancies between the current datatypes of the columns and their business significance.

### 3. Convert Claim Amount to Numeric
- Convert the `claim_amount` column to numeric datatype and remove the '$' sign.

### 4. Create Alert Flag for Unreported Claims
- Create an alert flag (1,0) for all injury claims that have gone unreported with the police.

### 5. Remove Duplicate Records
- Retain the most recent observation for each customer and delete any duplicated records based on the customer ID column.

### 6. Handle Missing Values
- Check for missing values and impute them with appropriate values (mean for continuous and mode for categorical).

### 7. Categorize Customers by Age
- Calculate the age of customers in years and categorize them into different age groups.

### 8. Average Claim Amount by Customer Segments
- Calculate the average amount claimed by customers from various segments.

### 9. Total Claim Amount by Incident Cause
- Calculate the total claim amount based on incident cause for claims made at least 20 days prior to October 1, 2018.

### 10. Insurance Claims by Age and Location
- Determine the number of adults from specific states who claimed insurance for driver-related issues and causes.

### 11. Pie Chart of Claim Amount by Gender and Segment
- Draw a pie chart showing the aggregated value of claim amount based on gender and segment.

### 12. Comparison of Claim Amounts by Gender
- Compare the claim amounts between males and females for driver-related issues using a bar chart.

### 13. Fraudulent Policy Claims by Age Group
- Visualize the maximum fraudulent policy claims by age group on a bar chart.

### 14. Monthly Trend of Total Claim Amount
- Visualize the monthly trend of the total claim amount.

### 15. Average Claim Amount by Gender, Age, and Fraud Status
- Represent the average claim amount for gender and age categories using a facetted bar chart.

## Statistical Analysis and Hypothesis Testing

### 16. Similarity in Claim Amounts by Gender
- Test if there's any similarity in the amount claimed by males and females.

### 17. Relationship Between Age Category and Segment
- Investigate if there's any relationship between age category and customer segment.

### 18. Rise in Claim Amounts Over Time
- Determine if the current year has shown a significant rise in claim amounts compared to the previous fiscal year.

### 19. Difference Between Age Groups and Insurance Claims
- Test if there's any difference between age groups and insurance claims.

### 20. Relationship Between Number of Policy Claims and Claimed Amount
- Investigate if there's any relationship between the total number of policy claims and the claimed amount.


