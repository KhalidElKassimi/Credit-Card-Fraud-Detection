# Credit-Card-Fraud-Detection

This repository contains a project on detecting credit card fraud using machine learning models. The project includes exploratory data analysis (EDA), data processing, and data modeling using various classifiers.

## EDA and Data Processing
In the EDA section, we explore the dataset to understand the distribution of classes, feature correlations, and other important aspects. Key steps include:

- Handling missing values
- Feature engineering
- Data normalization and scaling
- Visualizing data distributions and relationships

## Modeling
We use three different classifiers to build our models:

- Random Forest Classifier: An ensemble method that builds multiple decision trees and merges them to get a more accurate and stable prediction.

- AdaBoost Classifier: An ensemble technique that combines multiple weak classifiers to create a strong classifier. It adjusts the weights of incorrectly classified instances so that subsequent classifiers focus more on difficult cases.

- CatBoost Classifier: A gradient boosting algorithm that handles categorical features automatically and is known for its high performance and ease of use.

Each model is evaluated using cross-validation, and metrics such as accuracy, precision, recall, and F1-score are calculated.

Results
The results section in the notebook provides a comparison of the performance of each model. This includes:

- Confusion matrices
- ROC curves
- Precision-recall curves
- Feature importances
