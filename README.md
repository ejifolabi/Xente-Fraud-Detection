# Xente-Fraud-Detection
# Introduction
Fraud detection is a critical component of financial services, helping to prevent losses due to fraudulent activities. This project leverages machine learning techniques to build a high-performance fraud detection model.

# Dataset
The dataset used for this project consists of transaction records with features that describe each transaction. The dataset includes both legitimate and fraudulent transactions, providing a balanced view for model training and evaluation.

# Methodology
Methodology include:

Data Cleaning: Handling missing values and inconsistencies.
Exploratory Data Analysis (EDA): Understanding data distribution and relationships between features.
Feature Engineering: Creating new features that can enhance model performance.
Data Imbalancing: Techniques like oversampling, undersampling, and SMOTE to handle class imbalance.
Models
Several machine learning models were built and evaluated:

Support Vector Machine (SVM)
Decision Tree Classifier
Random Forest Classifier
K-Nearest Neighbors (KNN)
Evaluation
The models were evaluated using accuracy, precision, recall, and F1 score. The goal was to achieve an F1 score as close to 1 as possible.

Results
The Random Forest Classifier performed the best with the following metrics:

Accuracy: 0.99904
Precision: 0.998577
Recall: 0.999514
F1 Score: 0.999045
