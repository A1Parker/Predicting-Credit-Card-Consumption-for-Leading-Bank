# Predicting-Credit-Card-Consumption-for-Leading-Bank

## Credit Card Consumption Analysis

## Overview

This project analyzes customer spending behavior using credit card data. It involves data cleaning, exploratory data analysis (EDA), and predictive modeling to estimate future credit card consumption. The goal is to help banks optimize their marketing strategies and enhance customer relationship management.

## Business Context

Credit card usage insights are crucial for financial institutions to develop personalized offers, mitigate risks, and increase revenue. This project leverages customer demographics, behavioral data, and transaction history to predict future credit card spending.

## Dataset Details

The project uses three datasets:

Customer Demographics (CustomerDemographics.csv): Contains customer details such as age, gender, income level, and bank tenure.

Customer Behavior Data (CustomerBehaviorData.csv): Includes transaction history, liabilities, assets, and spending patterns over the last three months.

Credit Consumption Data (CreditConsumptionData.csv): Contains actual and missing credit card spending values for future predictions.

Data Preprocessing & Cleaning

Merging Datasets: Data was merged using Customer ID as the key.

Handling Missing Values:

Missing values in credit consumption were predicted using a trained model.

Numerical missing values were imputed using median values.

Categorical missing values were imputed using mode.

Data Type Adjustments: Columns were converted to appropriate data types.

Exploratory Data Analysis (EDA)

## Summary Statistics:

describe() was used to analyze distributions.

Categorical feature distributions were examined with frequency tables.

## Visualizations:

Histograms for numerical variables.

Bar charts for categorical variables.

Boxplots to identify outliers.

## Missing Value Imputation:

Heatmaps used to visualize missing data.

Imputation performed using statistical techniques (median/mode).

## Model Building & Evaluation

Model Used: Regression models were built using sklearn.

Target Variable: cc_cons (Average Credit Card Spend in the next three months).

## Training and Testing:

Data split into train (80%) and test (20%).

Feature selection performed to optimize model performance.

Model Performance Metrics:

Root Mean Square Percentage Error (RMSPE)

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score

## Key Insights

Identified high-spending customer segments based on income and tenure.

Customers with active personal loans tend to have lower spending.

Younger customers show more frequent transactions but lower spending per transaction.

Predicted credit consumption values for customers with missing data.

## Files in Repository

Credit_Card_Consumption_Analysis.ipynb - Jupyter Notebook with code and analysis.

CustomerDemographics.csv - Customer demographic dataset.

CustomerBehaviorData.csv - Customer spending dataset.

CreditConsumptionData.csv - Credit consumption dataset.

README.md - Project documentation (Read me).

## How to Use

Clone this repository: git clone https://github.com/A1Parker/CreditCardAnalysis.git

Open the Jupyter Notebook: Credit_Card_Consumption_Analysis.ipynb

Run all the cells to explore data and execute the model.

Future Enhancements

Implement deep learning techniques for improved predictions.

Incorporate additional behavioral factors to enhance the model.

Create an interactive Power BI dashboard for business stakeholders.
