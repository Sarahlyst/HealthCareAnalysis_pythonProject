# HEALTHCARE ANALYSIS

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tool Used](#tool-used)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [Recommendations](#recommendations)
- [Limitation](#limitation)
### Project Overview

As a data analyst for a fictitious organization called HealthConnect, a company providing innovative healthcare solutions. My objective is to analyze the organization’s patient database to discover trends and insights. The company is interested in identifying common health issues, treatment outcomes, and geographical distribution of diseases to better tailor its services. The project is designed to analyze patient data, discover trends, and build insightful dashboards to aid management in decision-making.

### Data Sources

Datasets used: I got the dataset from "[https://www.kaggle.com/datasets/prasad22/healthcare-dataset](https://www.kaggle.com/datasets/prasad22/healthcare-dataset)"

### Tool Used 
PYTHON  for
- Data Cleaning
- Data Analysis
- Data Visualization

### Data Cleaning
The dataset was first imported into python, then some cleaning operations were performed on it. Like checking for missing values, checking data info, checking and dropping duplicates, changing data types where appropriate, then saved the cleaned dataset.

### Exploratory Data Analysis
Exploration of the datasets was done to discover trends and insights on the organization’s patient database. some of the questions that were answered include:
- what is the gender distribution of patients in the dataset?
- most common medications prescribed for each medical condition
- what is the average length of stay for patients in the dataset?

### Data Analysis
Below is one of the interesting code I worked with to check the average billing amount for patients in the dataset

```python
avg_billing_amt = df['Billing Amount'].mean()
print(f'Average billing amount: {avg_billing_amt:.2f}')
```

### Results

- Demographic Analysis: from our analysis, it was discovered that our patient was more of the older ones. Also as for gender and blood type, the analysis of the dataset revealed a relatively even distribution.
- Medical Condition Analysis: Medical conditions and medications also revealed a relatively even distribution. There is no significant correlation between medical condition and age or gender. 
- Analysis on Admission and Discharge: The highest average of stay is 30 days while lowest is a day. Admission type is relatively evenly distributed and there is no correlation between admission type and medical condition or length of stay.
- Financial Analysis: The average billing amount for patients in the datset is 25539.32. Insurance provider is relatively evenly distributed and there is no correlation between billing amount and admission type or length of stay.
- Analysis on the quality of care: Test results and medication are evenly distributed, and there is no correlation between test results and medical condition or treatment outcome.
- Analysis  on Hospital and Doctoc: Hospitals and Doctors are also relatively evenly distributed among patients in the dataset. 
### Recommendations
Based on our analysis, the following actions are recommended:
- Regular checkups should be recommended for the middle age and elder ones since they have higher risk of getting sick.


### Limitation
The analysis of the dataset revealed a relatively even distribution of outcomes. We have some visualizations presented which illustrates the even distribution of values.
#### implications
The even distibution of outcomes has implications for analysis of data as it suggets several things like:
1) Randomness
2) No clear correlations
3) No dominant factors
4) Need for further investigation
5) implications for decision making   etc.



