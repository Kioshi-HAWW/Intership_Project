# Customer Churn Prediction using Logistic Regression

## Objective

The objective of this project is to build a Logistic Regression model to predict whether a telecom customer is likely to churn based on customer demographics and service usage.

## Dataset Link

https://www.kaggle.com/datasets/blastchar/telco-customer-churn

## Libraries Used

- pandas
- matplotlib
- scikit-learn

## Methodology

1. Loaded the dataset using Pandas.
2. Displayed the first five records.
3. Identified numerical and categorical features.
4. Converted the TotalCharges column to numeric values.
5. Handled missing values.
6. Encoded categorical variables using LabelEncoder.
7. Split the dataset into training and testing sets (80:20).
8. Applied StandardScaler to scale the features.
9. Built a Logistic Regression model.
10. Evaluated the model using Accuracy, Precision, Recall, F1 Score, and Confusion Matrix.

## Results

- Accuracy: 81.55%
- Precision: 67.71%
- Recall: 57.91%
- F1 Score: 62.43%



## Conclusion

The Logistic Regression model achieved good performance in predicting customer churn with an accuracy of 81.55%. The model successfully identified most customer churn cases while maintaining a good balance between precision and recall. Although Logistic Regression performs well, more advanced machine learning models may further improve prediction performance.