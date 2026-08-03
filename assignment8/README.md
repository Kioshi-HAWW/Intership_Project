# Assignment 8 — Handwritten Digit Recognition using ANN

## Objective
Develop an Artificial Neural Network (ANN) to classify handwritten digits (0–9) using the MNIST dataset, simulating an automated postal code digit recognition system.

## Dataset Link
MNIST Handwritten Digits Dataset (Kaggle):
https://www.kaggle.com/datasets/oddrationale/mnist-in-csv

> Note: The notebook loads MNIST automatically via `tensorflow.keras.datasets.mnist` (same dataset, official source), so no manual download is required to run it. The dataset itself is **not** included in this repository.

## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- tensorflow / keras
- scikit-learn

## Methodology
1. **Data Understanding** — Loaded the dataset into a Pandas DataFrame, inspected shape, structure, and visualized a sample digit.
2. **Data Preprocessing** — Checked for missing values, separated features/target, normalized pixel values to [0, 1], split into 80% train / 20% test, and one-hot encoded the labels.
3. **Model Development** — Built a Sequential ANN with two hidden layers, compiled with the Adam optimizer and categorical crossentropy loss, and trained for 10 epochs.
4. **Model Evaluation** — Evaluated test accuracy, generated a confusion matrix and classification report, and plotted accuracy/loss vs. epoch curves.

## Model Architecture
| Layer | Type | Neurons | Activation |
|---|---|---|---|
| Input | Dense | 784 | — |
| Hidden 1 | Dense | 128 | ReLU |
| Hidden 2 | Dense | 64 | ReLU |
| Output | Dense | 10 | Softmax |

**Optimizer:** Adam
**Loss:** Categorical Crossentropy
**Metric:** Accuracy
**Epochs:** 10

## Results
- **Test Accuracy:** _[fill in after running]_
- **Test Loss:** _[fill in after running]_
- Confusion matrix and classification report included in the notebook.
- Accuracy vs Epoch and Loss vs Epoch plots included in the notebook.

## Conclusion
_This project implemented an Artificial Neural Network to classify handwritten digits from the MNIST dataset, achieving a test accuracy of [insert your accuracy]. The model's two hidden layers (128 and 64 neurons with ReLU activation) allowed it to learn increasingly abstract, non-linear representations of pixel patterns — without them, the network would reduce to a simple linear classifier incapable of capturing the complex shapes that distinguish digits. One key advantage of Deep Learning over traditional Machine Learning is its ability to automatically learn features directly from raw pixel data, removing the need for manual feature engineering. However, a notable limitation of a plain ANN is that it treats each pixel independently and ignores spatial relationships between neighboring pixels, which convolutional architectures (CNNs) are better suited to exploit. Overall, the model performed well, though some confusion persisted between visually similar digits._
