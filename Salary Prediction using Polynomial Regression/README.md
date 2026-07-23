# Salary Prediction using Polynomial Regression

## Objective

The objective of this project is to predict employee salaries based on their position level using Polynomial Regression. The model is developed to capture the non-linear relationship between position level and salary.

---

## Dataset

Position Salaries Dataset

Kaggle Link:

https://www.kaggle.com/datasets/akram24/position-salaries

---

## Libraries Used

- pandas
- numpy
- matplotlib
- scikit-learn

---

## Methodology

1. Loaded the dataset using Pandas.
2. Displayed the first five records.
3. Identified the input feature and target variable.
4. Checked for missing values.
5. Split the dataset into 80% training and 20% testing.
6. Applied Polynomial Features with degree 3.
7. Trained the Polynomial Regression model.
8. Predicted salaries for the test data.
9. Evaluated the model using MAE, MSE and R² Score.
10. Visualized the original data and polynomial regression curve.

---

## Results

Mean Absolute Error (MAE): 70635.2459

Mean Squared Error (MSE): 6263853282.8603

R² Score: 0.8763

---

## Conclusion

Polynomial Regression successfully captured the non-linear relationship between position level and salary. The model achieved an R² score of 0.8763, indicating good prediction performance. Compared to Linear Regression, Polynomial Regression can model curved relationships and is more suitable for this dataset because salary does not increase in a straight-line pattern.