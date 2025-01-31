# Logistic Regression Model

# Dataset

## The dataset consists of:

1000 samples

10 features

2 classes (binary classification)

Generated using make_classification with random_state=15


# Implementation Steps

Import necessary libraries: pandas, numpy, matplotlib, seaborn, and scikit-learn.

Generate dataset: Using make_classification with 1000 samples and 10 features.

Exploratory Data Analysis (EDA):

Visualize feature distributions

Analyze class balance

Model Training:

Split dataset into training and testing sets

Train a logistic regression model using sklearn.linear_model.LogisticRegression

Hyperparameter Tuning & Cross-Validation:

Perform hyperparameter tuning using GridSearchCV

Compare accuracy before and after tuning

## Accuracy without GridSearchCV: 91%

## Accuracy with GridSearchCV: 92%

Model Evaluation:

Predict on test data

Calculate accuracy, confusion matrix, and classification report


## Results

Model accuracy and performance metrics are displayed at the end of the notebook.


## Hyperparameter tuning improved model accuracy from 91% to 92%.
