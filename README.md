# Salary Estimation using K-Nearest Neighbour

This project implements salary estimation using the K-Nearest Neighbour (KNN) algorithm. It predicts whether a person's salary is above or below $50K based on factors like age, education, capital gain, and hours worked per week.

## Overview

The project involves several steps:

1. **Importing Libraries**: Necessary libraries such as Pandas, NumPy, and scikit-learn are imported.
2. **Choose Dataset from Local Directory**: The dataset (`salary.csv`) is loaded from the local directory.
3. **Load Dataset**: The dataset is loaded into a Pandas DataFrame and summarized.
4. **Mapping Salary Data to Binary Value**: The income data is mapped to binary values (0 for <=50K, 1 for >50K).
5. **Segregate Dataset into X(Input/IndependentVariable) & Y(Output/DependentVariable)**: The dataset is split into input and output variables.
6. **Splitting Dataset into Train & Test**: The dataset is divided into training and testing sets.
7. **Feature Scaling**: Data is scaled to ensure all features contribute equally to the result.
8. **Finding the Best K-Value**: The optimal value of K for KNN is determined through error analysis.
9. **Training**: The KNN model is trained using the training data.
10. **Predicting New Employee's Salary**: The trained model is used to predict whether a new employee's salary will be above $50K.
11. **Prediction for all Test Data**: Predictions are made for all test data.
12. **Evaluating Model - CONFUSION MATRIX**: The model's performance is evaluated using a confusion matrix and accuracy score.

## Usage

To use this project:

1. Clone the repository.
2. Make sure you have Python installed along with necessary libraries mentioned in the project.
3. Run the provided code cells in a Jupyter Notebook or any Python environment.
