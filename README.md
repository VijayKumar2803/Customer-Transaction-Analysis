# Customer Transaction Analysis in the Banking Industry

## Overview

This project aims to predict which customers will make a specific transaction in the future. By leveraging machine learning techniques, we analyze customer transaction data to help Santander identify patterns and improve customer satisfaction, product recommendations, and financial health insights.

## Problem Statement

At Santander, our mission is to help people and businesses prosper. We aim to understand customers' financial behaviors to identify which products and services can help them achieve their monetary goals. This project focuses on a binary classification problem: predicting whether a customer will make a specific transaction in the future.

## Project Structure

1. **Data Exploration and Visualization**: Analyze the distribution and statistics of features.
2. **Data Preprocessing**: Prepare the data for model training, including handling missing values and feature scaling.
3. **Model Training**: Train various models such as Random Forest, Logistic Regression, and LightGBM.
4. **Model Evaluation**: Evaluate model performance using metrics like accuracy, ROC-AUC, and confusion matrix.
5. **Feature Importance**: Interpret feature importance using permutation importance and partial dependence plots.
6. **Handling Imbalanced Data**: Use SMOTE to address class imbalance.
7. **Final Predictions**: Generate final predictions on the test data and save the results.

## Data

- **Train Data**: Contains customer transaction information with labels indicating whether a specific transaction will occur.
- **Test Data**: Contains customer transaction information without labels, used for making final predictions.

## Usage

1. **Data Exploration and Visualization**: Analyze target class distribution and feature distributions.
2. **Data Preprocessing**: Prepare data for model training, including handling missing values and feature scaling.
3. **Model Training**: Train a RandomForestClassifier and other models like Logistic Regression and LightGBM.
4. **Model Evaluation**: Evaluate the models using ROC-AUC, confusion matrix, and classification report.
5. **Feature Importance**: Use ELI5 to interpret feature importance and Partial Dependence Plots for detailed analysis.
6. **Handling Imbalanced Data**: Implement SMOTE to balance the dataset.
7. **Final Predictions**: Generate predictions on the test data and save the results to a CSV file.

## Results

The results of the model predictions are saved in `submission.csv`, which can be submitted for evaluation.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
