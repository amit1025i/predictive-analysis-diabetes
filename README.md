# Diabetes Prediction using Logistic Regression

This project aims to build a machine learning model to predict diabetes outcomes using logistic regression. It covers the entire pipeline, including data preprocessing, handling class imbalance, feature scaling, model training, and evaluation.

## Dataset
The dataset used in this project contains various medical features that are used to predict the likelihood of diabetes. You can replace the dataset with your own CSV file if needed.

## Project Steps
1. **Data Preprocessing:**
   - Handling missing values
   - Outlier detection and removal
   - Feature scaling using StandardScaler

2. **SMOTE for Imbalanced Data:**
   - The Synthetic Minority Over-sampling Technique (SMOTE) is applied to balance the dataset.

3. **Model Training:**
   - A logistic regression model is trained on the processed data.

4. **Model Evaluation:**
   - The model's performance is evaluated using accuracy, confusion matrix, and classification report.

5. **Model Persistence:**
   - The trained model is saved using the `pickle` module for future use.

## Installation

To run this project locally, make sure you have the following dependencies installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
