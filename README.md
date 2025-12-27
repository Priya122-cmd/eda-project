# Loan Sanction – Exploratory Data Analysis (EDA)

## Exploratory Data Analysis on Loan Sanction Dataset  
📊 Loan Sanction Dataset | EDA

## Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) on a Loan Sanction dataset consisting of 614 records with 13 features.  
The objective is to analyze patterns influencing loan approvals and rejections, address missing data issues, and determine the most important factors affecting loan sanction decisions.

## Problem Statement
Loan approval decisions in financial institutions are often complicated by:
- Incomplete and inconsistent applicant information  
- Presence of missing values  
- Imbalance between approved and rejected applications  

Through EDA techniques, this project cleans, preprocesses, and examines loan data to extract meaningful insights related to applicant eligibility and approval trends.

## Dataset Details
- Total Records: 614 applicants  
- Total Features: 13  
  - 8 categorical  
  - 5 numerical  
- Target Variable: Loan Status (Approved / Rejected)

**Key Columns Include:**  
Loan ID, Gender, Married, Dependents, Education, Self Employed,  
Applicant Income, Co-applicant Income, Loan Amount, Loan Term,  
Credit History, Property Area, Loan Status.

## Data Preprocessing
The following preprocessing steps were applied:
- Handling missing values (Mode for categorical features, Median for numerical features)
- Converting data types (Dependents converted to integer)
- Detecting outliers in income and loan amount variables
- Encoding categorical variables to support analysis

## Analysis and Insights

### Univariate Analysis
- Applicant Income and Loan Amount distributions are right-skewed with noticeable outliers
- Majority of applicants are male and belong to semi-urban areas
- Most applicants have a valid credit history, which is strongly associated with loan approval

### Bivariate Analysis
- Credit history emerges as the strongest factor influencing loan approval
- Higher combined income of applicant and co-applicant improves approval probability
- Married applicants and graduates show slightly higher approval rates
- Applicants from rural areas receive fewer approvals compared to urban and semi-urban regions

### Multivariate Analysis
- A moderate correlation exists between income and requested loan amount
- Loan approvals span across multiple income levels, indicating income alone is not decisive
- Credit history remains the dominant factor in approval decisions

## Conclusion
- Credit history plays the most significant role in loan approval, followed by income and property area
- Demographic attributes such as education, marital status, and employment type have a secondary influence
- Proper treatment of missing values, outliers, and class imbalance is crucial for dependable predictive analysis

## Tools Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter Notebook  

## Collaboration
Developed in collaboration with A.Laxmi Priya, P.Greeshma, and I.Lalitha.  
Special thanks to Lakshmi Teja Illuri Mam, Program Manager Raghu Ram Aduri Sir, Placement Officer Sigilipelli Yeshwanth Sir, and Innomatics Research Labs for their guidance and support.

## Hashtags
#EDA #DataAnalysis #Python #DataScience #LoanPrediction #FinancialAnalytics #Pandas #Seaborn #Matplotlib #PortfolioProject #CareerGrowth



