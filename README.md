# Customer Churn Analysis - README

This project analyzes customer churn for a telecom company using machine learning techniques. The goal is to predict which customers are at risk of churning and identify the most important factors that contribute to churn. 

The analysis is divided into six parts:

1. Introduction and Business Problem
2. Data Preparation and Exploration
3. Classification Analysis
4. Feature Importance
5. Data Summary and Implications
6. Demonstration

## Requirements

To run the code, you will need the following packages:

- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib

## Usage

To reproduce the analysis, run the Jupyter notebook `Classification Analysis.ipynb`. The notebook includes all the code used for data preparation, exploration, and machine learning models. 

The data used in this project is located in the `data` folder. The `churn_clean.csv` file contains the customer data used for the analysis.

## Results

The analysis found that customers on a month-to-month contract, with a high monthly charge, and using streaming services are at the highest risk of churning. The KNN model had an accuracy rate of 83.64% and an AUC of 0.89, indicating that it could distinguish well between positive and negative churn classes. However, the false-negative rate (FNR) was more than double the false-positive rate (FPR), indicating that the model could be improved by adding more significant features or reducing noise.
