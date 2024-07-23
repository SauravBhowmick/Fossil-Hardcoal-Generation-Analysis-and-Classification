# EDE2_Project2
Machine learning - Supervised Learning

## Fossil Hardcoal Generation Analysis and Classification
This repository contains scripts and models for analyzing actual generation data for fossil hardcoal technology. The project involves exploratory data analysis, binary classification, and evaluation of multiple machine learning models to predict energy generation patterns.

### Features:
#### Exploratory Data Analysis:
- Create a binary classification setting with labels "High" and "Low" using a threshold of 3000MW.
- Generate three meaningful visualizations exploring the relationship between features and target variables.
- Include two heatmaps (x: day of year, y: time of day) for the target variable:
  - Continuous variable
  - Binary variable

#### Logistic Regression and k-Nearest Neighbors (kNN):
- Implement and train a logistic regression model, identifying optimum parameters.
- Implement and train a kNN model, identifying optimum hyperparameters.
- Plot showing train and test scores.
- Evaluate and compare kNN and logistic regression models:
- Compare all relevant scores (Accuracy, Recall, Precision, F1-Score, ROC_AUC, MCC).
- Visualize confusion matrix and ROC plot.
- Explain the default scoring value (ROC_AUC is preferred due to training set imbalance).

#### Decision Tree:
- Model evaluation with cross-validation.
- Visualize the decision tree.
- Visualize feature importance.

#### Comparison of Multiple Classification Models:
- Apply and compare 5 different classification models:
  - Logistic Regression
  - kNN
  - Random Forests
  - Gradient Boosting
  - AdaBoost
- Perform cross-validation and hyperparameter optimization for all models.
- Select the best performing model based on ROC_AUC score and explain the choice.

#### Deployment of Best Performing Model:
- Train and fit the best performing model, named "best_model".
- Deploy the best model on 2024 data (not used for training).
- Evaluate and visualize predictions on the test dataset.
