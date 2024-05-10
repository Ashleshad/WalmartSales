# WalmartSales
# Walmart Sales Prediction

## Introduction
This repository contains Python code for predicting customer ratings on Walmart sales using machine learning algorithms. The dataset used in this project is 'Walmart Sales.csv'. The code demonstrates data preprocessing, exploratory data analysis (EDA), and the application of machine learning models for prediction.

## Requirements
Ensure you have Python installed. You'll also need the following libraries:
- pandas
- matplotlib
- seaborn
- scikit-learn

## Usage
1. Clone this repository to your local machine.
2. Install the required libraries using pip: `pip install -r requirements.txt`.
3. Run the Jupyter Notebook or Python script to execute the code.
4. Adjust parameters and experiment with different algorithms as needed.

## Contents
- `Walmart Sales.csv`: Dataset containing Walmart sales data.
- `Walmart_Sales_Prediction.ipynb`: Jupyter Notebook containing the Python code.
- `README.md`: Readme file with instructions and information about the project.

## Instructions
1. Import necessary libraries.
2. Read the dataset.
3. Perform data preprocessing:
    - Handle missing values.
    - Convert categorical columns to numerical using Label Encoding.
    - Drop unnecessary columns.
4. Explore the data using EDA techniques:
    - Summary statistics.
    - Distribution of ratings.
    - Correlation heatmap.
5. Split the dataset into training and testing sets.
6. Apply machine learning algorithms:
    - Random Forest Regressor
    - Linear Regression
    - Decision Tree Regressor
7. Evaluate model performance using metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R2).
8. Choose the best-performing model for predicting customer ratings.

## Summary
Among the applied machine learning algorithms, Logistic Regression seems to be the best performer for predicting customer ratings on Walmart sales based on the evaluation metrics.
