# Breast Cancer Classification using K-Nearest Neighbors (KNN)

## Objective

The objective of this project is to develop a K-Nearest Neighbors (KNN) classification model to predict whether a breast tumor is Malignant (M) or Benign (B) using the Breast Cancer Wisconsin Diagnostic Dataset.

## Dataset

Breast Cancer Wisconsin Diagnostic Dataset

Kaggle Dataset:
https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

## Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Methodology

1. Loaded the dataset using Pandas.
2. Displayed the first five records.
3. Identified numerical features and the target variable.
4. Checked dataset information and summary statistics.
5. Verified that there were no missing values.
6. Removed unnecessary columns.
7. Encoded the target variable.
8. Standardized all feature values using StandardScaler.
9. Split the dataset into 80% training and 20% testing.
10. Trained a K-Nearest Neighbors classifier with K = 5.
11. Predicted the test dataset.
12. Evaluated the model using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.

## Results

The KNN classifier achieved high classification performance on the test dataset. The evaluation metrics indicate that the model successfully classified most breast cancer cases with very few incorrect predictions.

The generated confusion matrix is available as **confusion_matrix.png**.

## Conclusion

The K-Nearest Neighbors model successfully classified breast tumors as malignant or benign after applying data preprocessing and feature scaling. Feature scaling improved the performance because KNN relies on distance calculations between data points. The model achieved high accuracy along with strong precision, recall, and F1-score values. One limitation of KNN is that prediction becomes slower as the training dataset grows larger because distances must be calculated for every new sample. Overall, the model demonstrated good performance for breast cancer classification using the provided dataset.