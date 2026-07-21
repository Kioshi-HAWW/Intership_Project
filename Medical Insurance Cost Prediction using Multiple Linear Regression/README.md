# Medical Insurance Cost Prediction using Multiple Linear Regression

## Objective

The objective of this project is to develop a Multiple Linear Regression model to predict medical insurance charges using customer information such as age, sex, BMI, number of children, smoker status, and region.

## Dataset Link

https://www.kaggle.com/datasets/mirichoi0218/insurance

## Libraries Used

- Pandas
- Matplotlib
- Scikit-learn

## Methodology

1. Loaded the dataset using Pandas.
2. Displayed the first five records.
3. Identified numerical and categorical features.
4. Checked for missing values.
5. Encoded categorical variables using LabelEncoder.
6. Split the dataset into 80% training and 20% testing.
7. Trained a Multiple Linear Regression model.
8. Evaluated the model using MAE, MSE, and R² Score.
9. Created an Actual vs Predicted scatter plot.

## Results

The Multiple Linear Regression model achieved a good R² score and was able to predict insurance charges with reasonable accuracy. The scatter plot showed that the predicted values follow the actual values closely.

## Conclusion

The model successfully predicts medical insurance charges using customer information. Smoker status, age, and BMI have a significant effect on insurance charges. Although the model performs well, Linear Regression may not capture complex non-linear relationships present in the data.