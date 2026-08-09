# Reducing Customer Churn Through Business-Focused Data Analysis 

## Executive Summary 

This project analyzes telecom customer churn to identify the customer segments most at risk of leaving the company. The analysis shows that customers with month-to-month contracts, short tenure, higher monthly charges, electronic check payment methods, and no support or security services exhibit the highest churn risk. 

The project focuses on **business-oriented exploratory data analysis and retention recommendations**, rather than predictive modeling. 

--- 

## Business Problem 

Customer churn reduces recurring revenue and increases customer acquisition costs. Understanding which customers are most likely to leave and what business factors are associated with churn can help prioritize retention efforts more effectively. 

### Business Questions 

- Which customers are most likely to churn?
- What business factors are associated with churn?
- Which customer segment should be prioritized for retention?
- What actions could potentially reduce churn?

### Objectives 

- Measure the overall churn rate
- Identify the strongest churn drivers
- Segment high-risk customers
- Provide actionable retention recommendations

--- 

## Dataset 
- **Source:** IBM Telco Customer Churn dataset (publicly available on Kaggle)
- **Records:** 7,043 customers (7,032 after cleaning)
- **Features:** 21 customer and service-related variables

Dataset link: https://www.kaggle.com/datasets/blastchar/telco-customer-churn 

--- 

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

--- 

## Project Workflow 

1. Data understanding
2. Data cleaning
3. Exploratory analysis
4. Business insight generation
5. Retention recommendations

--- 

## Key Insights 

### 1. Month-to-month customers have the highest churn risk

Customers without long-term contracts churn substantially more than one-year and two-year contract customers. 

### 2. Customers with short tenure churn more frequently

Churn is concentrated in the early stages of the customer lifecycle. 

### 3. Higher monthly charges are associated with higher churn 

Customers paying more per month are more likely to leave, suggesting sensitivity to perceived value. 

### 4. Electronic check customers show elevated churn 

Payment behavior appears to be associated with retention outcomes. 

### 5. Customers without TechSupport or OnlineSecurity are less retained 

Service attachment may play an important role in customer retention. 

--- 

## Business Impact 

The analysis identifies a high-risk customer segment characterized by: 
- Month-to-month contract
- Short tenure
- High monthly charges
- Electronic check payment method
- No TechSupport or OnlineSecurity

Focusing retention efforts on this segment can help reduce churn concentration and improve the efficiency of retention campaigns. 

--- 

## Retention Recommendations 

### Improve early customer retention 

- Provide onboarding support during the first 3-12 months
- Monitor new customers with high monthly charges

### Encourage longer-term contracts 

- Offer incentives to migrate from month-to-month plans to annual plans

### Target electronic check customers 
- Promote automatic payment methods through discounts or convenience benefits

### Increase adoption of support services 
- Bundle TechSupport and OnlineSecurity with internet plans

### Prioritize high-value customers 
- Focus retention efforts on customers with higher monthly charges

--- 

## Repository Structure 
reducing-customer-churn-business-analysis/ 
├── data/ 
│ └── telco_churn.csv 
├── notebooks/ 
│ └── customer_churn_analysis.ipynb 
├── images/ 
└── README.md 

--- 

## How to Run 
1. Clone this repository
2. Install the required libraries
3. Open the notebook in Jupyter Notebook or VS Code
4. Run all cells sequentially

--- 

## Notebook 

Main analysis notebook: 

- `notebooks/customer_churn_analysis.ipynb`

--- 

## Conclusion

The analysis shows that churn is primarily associated with **low contract commitment, short customer tenure, higher monthly charges, electronic check payment behavior, and the absence of support and security services**. 

These findings provide a clear foundation for targeted retention initiatives and demonstrate how business-focused data analysis can support customer retention decision-making.
