# Bank Customer Churn Analysis – Power BI Dashboard  
Customer Churn Risk Analysis and Segmentation for a European Bank  

## Short Description  
This project analyzes customer churn behavior using a dataset of 10,000 customers from a European bank. The objective was to identify key drivers of churn, evaluate behavioral and regional differences, and segment customers based on churn risk to support data-driven retention strategies.

The analysis focuses on measurable churn indicators such as engagement level, product ownership, age distribution, and geographic differences.

## Tech Stack  
- Power BI Desktop  
- DAX (custom measures and calculated columns)  
- Power Query (data transformation and cleaning)  
- CSV dataset  

## Data Source  
The dataset contains account-level information for 10,000 customers, including:
- Demographics: Age, Gender, Geography  
- Financial attributes: Balance, Credit Score, Estimated Salary  
- Behavioral attributes: Number of Products, Active Status  
- Target variable: Churn status (Exited = 1, Retained = 0)  

Dataset sourced from Maven Analytics – Customer Churn dataset.

## Features and Highlights  
- Churn rate calculation using DAX measures  
- Geographic churn comparison (France, Germany, Spain)  
- Behavioral analysis (Activity status and product count impact)  
- Age-based churn distribution analysis  
- Risk-based customer segmentation (High / Medium / Low)  
- Executive-style Power BI dashboard focused on business interpretation  

## Key Insights  
- France represents the largest customer base (~50%), while Germany and Spain each account for ~25%.  
- Germany has the highest churn rate (~32%), nearly double that of France and Spain (~16%).  
- Inactive customers churn at significantly higher rates than active members.  
- Customers holding only one product exhibit substantially higher churn compared to multi-product customers.  
- Churn increases notably in the 40–60 age segment.  
- Salary and tenure show relatively weak influence on churn behavior.

## Business Implications  
Churn is primarily driven by engagement level, product depth, age segment, and geographic variation rather than income or tenure.

Retention efforts should focus on:
- Reducing churn risk in Germany  
- Increasing engagement among inactive customers  
- Promoting multi-product adoption  
- Monitoring middle-aged customer segments


