# Credit_Card_Default
Credit_Card_Default

## Overview
In this project, I explored the prediction of credit card default using various machine learning models. Key factors influencing default include gender, education level, credit limit, and age. Males tend to have a slightly higher default rate, while younger individuals and those with lower credit limits show a greater propensity for default. Education plays a significant role, particularly among university and graduate students.

## Details
In this project, I utilized three main sampling techniques: SMOTE, Undersampling, and Oversampling, along with four evaluation metrics: Accuracy, Precision, Recall, and F1-score. To predict credit card defaults, I applied basic machine learning models such as Logistic Regression, as well as more advanced models like Decision Tree, Random Forest, SVM, Gradient Boosting, and XGBoosting. 

I also performed hyperparameter tuning using GridSearch CV and applied different train-test split ratios of 0.8-0.2, 0.7-0.3, and 0.5-0.5 for all three sampling methods. The results of these experiments are presented in the report and detailed in the final results section.

## Result
The analysis demonstrated that Random Forest and Gradient Boosting models consistently performed the best, especially when the data was balanced using SMOTE. Among the data balancing techniques, SMOTE yielded the most reliable results, whereas undersampling led to the lowest model performance. We also observed that the choice of train-test split ratio (0.8-0.2) significantly impacted model performance, with this split producing the highest accuracy and AUC scores.

These insights can guide credit institutions in effectively managing risk, enabling them to create tailored lending strategies to minimize default rates.
