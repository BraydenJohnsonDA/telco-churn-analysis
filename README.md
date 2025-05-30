# Telco Customer Churn Analysis

## Project Overview

This project explores customer churn data from a telecommunications company to identify patterns and drivers of churn. The goal is to deliver actionable business insights that can support customer retention strategies and reduce revenue loss due to churn.

The analysis was conducted using Python in a Jupyter Notebook environment and focuses on answering key questions such as:
- What types of customers are more likely to churn?
- What features are most strongly correlated with churn?
- How do payment methods, contract types, and tenure influence churn rates?

## Dataset

The dataset used in this project is the **Telco Customer Churn** dataset by Abdallah Wagih, available on Kaggle. It includes detailed customer data from a U.S.-based telecom provider, with information on:

- Demographics (e.g., senior status, gender)
- Service subscriptions (e.g., internet, phone, streaming)
- Account and billing information (e.g., contract type, payment method, tenure)
- Churn labels and reasons

**Source:** [Telco Customer Churn Dataset on Kaggle](https://www.kaggle.com/datasets/abdallahwagih/telco-customer-churn)

## Tools and Libraries
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- Excel for initial data format

## Key Findings

- **Contract Type**: Month-to-month customers churned at a rate of 42.7%, while only 2.8% of two-year contract customers churned.
- **Payment Method**: Customers using electronic checks churned at 45.3%, significantly higher than those using automatic payment methods.
- **Tenure**: Churn was highest among newer customers, especially within the first few months.
- **Internet Service**: Fiber optic users had the highest churn rate at 41.9%, compared to 19.0% for DSL.
- **Senior Citizens**: Churn among senior citizens was slightly higher than among non-seniors.

## Business Recommendations

Based on the analysis, the following strategies are recommended to reduce churn:
1. Incentivize long-term contracts through discounts or bundled service offerings.
2. Encourage automatic payment methods to reduce churn linked to manual billing.
3. Develop onboarding and early engagement programs to retain new customers.
4. Investigate causes of dissatisfaction among fiber optic customers.
5. Tailor support and outreach efforts toward high-risk segments, including month-to-month and electronic check users.

## Next Steps

This analysis could be extended by:
- Building a predictive churn model using logistic regression or decision trees.
- Segmenting customers by risk level for targeted retention strategies.
- Tracking churn trends over time to detect seasonality or campaign effects.

## Repository Contents

- `Telco_Customer_Churn_Analysis.ipynb`: Complete Jupyter Notebook with data cleaning, exploratory analysis, visualizations, and insights.

## How to Open the Notebook

The analysis is provided in a Jupyter Notebook file (`.ipynb` format). To open it:

1. Clone or download this repository.
2. Open the file using [Jupyter Notebook](https://jupyter.org/install) or [JupyterLab](https://jupyterlab.readthedocs.io/), available through Anaconda or pip installation.
3. Alternatively, you can view the notebook directly on GitHub without downloading.

For best results, open the notebook in Jupyter to run the code interactively and explore the visualizations.
