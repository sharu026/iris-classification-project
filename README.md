# iris-classification-project
# Iris Flower Classification using Machine Learning

## Project Overview
This project focuses on classifying iris flower species using machine learning algorithms. The Iris dataset contains flower measurements such as sepal length, sepal width, petal length, and petal width. The objective is to predict the species of the flower based on these features.

## Dataset
Dataset used:
https://www.kaggle.com/datasets/bhanupratapbiswas/iris-classification-dataset

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

## Machine Learning Algorithms
The following algorithms were trained and compared:
- K-Nearest Neighbors (KNN)
- Logistic Regression
- Decision Tree Classifier

## Exploratory Data Analysis (EDA)
Performed:
- Dataset inspection
- Null value checking
- Pairplot visualization
- Correlation heatmap
- Class separability analysis

## Evaluation Metrics
Models were evaluated using:
- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1-Score

## Best Model
K-Nearest Neighbors (KNN) achieved the best performance for this dataset.

## Saved Model
The trained model is saved as:

```text
iris_model.pkl
```

---

## Example Inference Code

```python
import joblib

# Load trained model
model = joblib.load("iris_model.pkl")

# Example flower measurements
sample = [[5.1, 3.5, 1.4, 0.2]]

# Predict species
prediction = model.predict(sample)

print("Predicted Class:", prediction)
```

## Project Files

```text
Iris_Project/
│
├── Iris.csv
├── Iris_Classification.ipynb
├── Iris_Classification.html
├── iris_model.pkl
├── README.md
├── screenshots/
```

## Author
Sharanya N
