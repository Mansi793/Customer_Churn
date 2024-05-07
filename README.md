# Customer_Churn


# Handling Imbalanced Data in Bank Customer Churn Prediction

The churn variable has imbalanced data. So, the solution to handle imbalanced data are:

- **Resample Training set**
- **Use K-fold Cross-Validation in the Right Way**
- **Ensemble Different Resampled Datasets**

## Data Preparation

We have to change the value in the Country and Gender columns so the Machine Learning model can read and predict the dataset. After changing the value, we have to change the data types on the Country and Gender column from string to integer because XGBoost Machine Learning Model cannot read string data types even though the value in the column is number.

## Choosing the Best Algorithm

Lastly, XGBoost and Random Forest are the best algorithms to predict Bank Customer Churn since they have the highest accuracy (86.85% and 86.45% respectively). Random Forest and XGBoost have perfect AUC Scores. They have 0.8731 and 0.8600 AUC Scores.
