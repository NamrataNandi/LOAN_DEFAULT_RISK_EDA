# Loan Default Risk – Exploratory Data Analysis

Exploratory data analysis on loan applicant data to identify key indicators of loan default, supporting evidence-based lending decisions.

## What this covers
- Missing value treatment using skewness-based imputation (mean/median/mode)
- Outlier detection and treatment using the IQR method
- Univariate, bivariate, and multivariate analysis
- Correlation analysis comparing defaulters vs. non-defaulters
- Identification of class imbalance in the target variable (~92% non-defaulters vs. ~8% defaulters)

## Key findings
- Applicants on maternity leave show a higher default rate and are not ideal target clients
- Clients working as laborers show higher default rates than other occupation types
- Car ownership correlates with lower default rates
- Revolving loans show a lower proportion of defaults compared to other loan types

## Tools
Python (pandas, numpy, matplotlib, seaborn) in Jupyter Notebook
