# Admission Prediction Model for University Applicants using Logistic Regression

## Project Overview
This project aims to implement logistic regression to predict the likelihood of university admission based on multiple features such as exam scores and other applicant data. Logistic regression is a classification algorithm that maps input features to a probability score between 0 and 1, helping in binary classification tasks like admission prediction.


## Problem Statement
The goal is to build a logistic regression model that can accurately classify whether an applicant will be admitted to a university or not based on their performance in entrance exams. The dataset contains exam scores as input features and the admission status as the target variable.


## Project Workflow

### Step 1: Data Loading and Exploration
- Load the dataset containing exam scores and admission status.
- Visualize the data distribution to understand the correlation between features and target variables.

### Step 2: Sigmoid Function Implementation
- The sigmoid function maps the input data to a probability between 0 and 1. It is defined as:
  \[
  \sigma(z) = \frac{1}{1 + e^{-z}}
  \]

### Step 3: Cost Function and Gradient Descent
- The cost function for logistic regression measures the error between predicted and actual values. It is optimized using gradient descent to update model parameters.

### Step 4: Decision Boundary
- The decision boundary is a line that separates positive and negative classes based on the model's predictions.
- Visualize the decision boundary to assess the model's performance.

### Step 5: Model Evaluation
- Calculate accuracy, precision, recall, and F1-score to evaluate the model's performance on the training and testing datasets.

### Step 6: Regularized Logistic Regression
- Regularization (L2) is implemented to prevent overfitting and improve generalization on unseen data.

## Results
- The logistic regression model achieves high accuracy in predicting admission status based on exam scores.
- Regularization helps reduce overfitting and improves the model's performance on complex datasets.

## Future Scope
- Adding more features like GPA, extracurricular activities, and recommendation letters can enhance prediction accuracy.
- Implementing other classification algorithms like Support Vector Machines and Neural Networks for comparison.

