# Dynamic-Ride-Pricing

## Project Overview
This project aims to predict cab fares by considering factors beyond distance, such as weather conditions, time of day, and day of the week. The goal is to enhance customer trust and satisfaction while ensuring driver comfort and profitability.

## Problem Statement
Current fare calculation systems primarily focus on distance, neglecting critical factors that impact rides, such as bad weather, traffic conditions, time of day, and peak demand periods. This oversight can lead to driver challenges, customer frustration, and increased operational costs, ultimately affecting business viability.

## Plan of Action
* **Data Collection & Pre-processing:** Gather and clean data to ensure quality and consistency.
* **Exploratory Data Analysis (EDA):** Identify patterns, anomalies, and insights through statistical analysis and visualizations.
* **Data Preparation:** Use label encoding and binning to convert data into a machine-readable format and reduce noise.
* **Feature Selection:** Implement Recursive Feature Elimination (RFE) to identify and retain the most relevant features.
* **Modeling & Testing:** Train and validate multiple machine learning models, including Linear Regression, Random Forest, Decision Tree, and Gradient Boosting Regressor.
* **Results Evaluation:** Assess model performance using MAE, MSE, and RMAE metrics, presenting findings in a tabular format comparing actual vs. predicted values.

## Conclusion
The project successfully predicts cab fares considering multiple factors, with the Gradient Boosting Regressor yielding the best performance (MAE: 1.017, MSE: 2.587, RMAE: 1.608). Implementing this model can significantly improve customer satisfaction and driver welfare.
