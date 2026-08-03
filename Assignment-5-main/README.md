# Employee Attrition Prediction using Decision Tree and Random Forest

## Objective

The objective of this project is to predict whether an employee is likely to leave the organization using machine learning classification models. Two models, Decision Tree and Random Forest, are developed and their performance is compared using different evaluation metrics.

---

## Dataset Link

IBM HR Analytics Employee Attrition & Performance Dataset

https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

---

## Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Methodology

1. Loaded the employee attrition dataset using Pandas.
2. Displayed the first five records.
3. Identified numerical and categorical features.
4. Displayed dataset information and summary statistics.
5. Checked for missing values.
6. Removed unnecessary columns.
7. Encoded categorical variables using Label Encoding.
8. Split the dataset into 80% training and 20% testing data.
9. Trained a Decision Tree Classifier.
10. Trained a Random Forest Classifier with 100 estimators.
11. Evaluated both models using Accuracy, Precision, Recall and F1-Score.
12. Generated confusion matrices.
13. Plotted feature importance for the Random Forest model.
14. Compared the performance of both models.

---

## Results

| Metric | Decision Tree | Random Forest |
|---------|--------------:|--------------:|
| Accuracy | 75.85% | 87.07% |
| Precision | 11.90% | 57.14% |
| Recall | 12.82% | 10.26% |
| F1-Score | 12.35% | 17.39% |

---

## Model Comparison

- Random Forest achieved higher accuracy than the Decision Tree model.
- Random Forest produced much higher precision and a slightly better F1-score.
- Both models had low recall because the dataset contains more employees who stayed than employees who left.
- Random Forest identified MonthlyIncome, OverTime, Age, DailyRate and TotalWorkingYears as the most important features affecting employee attrition.

---

## Conclusion

The Random Forest model performed better than the Decision Tree model for employee attrition prediction. It achieved higher accuracy and precision, making it more reliable for this dataset. Random Forest reduces overfitting by combining multiple decision trees, whereas a single Decision Tree can easily overfit the training data. Although Random Forest requires more computational resources, it provides better overall predictive performance and is a suitable choice for this classification problem.