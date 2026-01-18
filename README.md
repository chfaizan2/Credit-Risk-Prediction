# Credit-Risk-Prediction
## ○ The Task Objective

The objective of this task was to analyze a loan application dataset to understand customer behavior, identify factors influencing loan default, and build a predictive model to classify applicants as defaulters or non-defaulters.

## ○ Your Approach

The dataset was explored using descriptive statistics and extensive exploratory data analysis. Columns with high missing values were removed, unnecessary features were dropped, and remaining null values were handled using mean and mode imputation. Negative day values were converted to absolute form for better interpretability.
Categorical and numerical features were analyzed against the target variable using heatmaps, bar plots, histograms, and defaulter ratio analysis. Feature scaling and label encoding were applied, followed by class balancing using SMOTE. Important features were selected, and a Logistic Regression model was trained and evaluated using standard classification metrics.

## ○ Results and Insights

The analysis revealed strong relationships between loan default and features such as income level, credit amount, employment duration, education level, and external source scores. Class imbalance was successfully handled using SMOTE, leading to improved model learning. The Logistic Regression model achieved reliable performance, as reflected by accuracy, precision, recall, F1-score, confusion matrix, and ROC-AUC curve. These results indicate that the selected features and preprocessing steps were effective in predicting loan default risk.
