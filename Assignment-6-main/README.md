# Weather Condition Classification using Support Vector Machine (SVM)

## Objective

This project develops a Support Vector Machine (SVM) classification model using weather data collected from the Open-Meteo API. The model classifies weather conditions into **Warm** and **Cool** categories based on temperature values.

---

## Dataset

The dataset is fetched dynamically from the Open-Meteo API whenever the notebook is executed. No separate dataset download is required.

API Documentation:
https://open-meteo.com/

Features used:

- Temperature
- Relative Humidity
- Surface Pressure
- Wind Speed

Target Variable:

- Warm → Temperature ≥ 25°C
- Cool → Temperature < 25°C

---

## Libraries Used

- pandas
- requests
- matplotlib
- scikit-learn

---

## Methodology

1. Collected weather data from the Open-Meteo API.
2. Converted the JSON response into a Pandas DataFrame.
3. Created the Weather_Class target variable.
4. Checked for missing values.
5. Encoded the target variable.
6. Split the dataset into training and testing sets.
7. Standardized the feature values using StandardScaler.
8. Trained an SVM classifier with the RBF kernel.
9. Evaluated the model using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.

---

## Results

The SVM classifier successfully classified weather conditions into Warm and Cool categories. Model performance was evaluated using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.

---

## Conclusion

The project demonstrates the use of Support Vector Machine (SVM) for weather classification using data obtained from the Open-Meteo API. Feature scaling improved model performance, and the RBF kernel effectively classified the weather conditions. SVM performs well for classification tasks but can become computationally expensive when working with very large datasets.