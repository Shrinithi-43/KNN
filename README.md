# 🌸 K-Nearest Neighbors (KNN) Classification – Iris Dataset

This project demonstrates the implementation of the **K-Nearest Neighbors (KNN)** algorithm using the **Iris dataset**. The goal is to classify iris flowers into three species based on features such as petal and sepal length and width.

---

## 📌 Objective
To understand and implement the KNN algorithm for classification and evaluate its performance using metrics like accuracy and confusion matrix.

---

## 📁 Dataset
- **Name**: Iris Dataset  
- **Source**: [UCI Machine Learning Repository](https://www.kaggle.com/datasets/uciml/iris)
- **Features**:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- **Target**: Species (`setosa`, `versicolor`, `virginica`)

---

## 🧪 Tools Used
- Python
- Scikit-learn
- Pandas
- Matplotlib
- NumPy

---

## ⚙️ Steps Performed
1. **Loaded** the Iris dataset.
2. **Normalized** the features using `StandardScaler`.
3. **Split** the dataset into training and testing sets.
4. **Trained** the KNN model with different values of K (1–10).
5. **Evaluated** model accuracy for each K.
6. **Visualized** accuracy vs. K.
7. **Selected** the best K and evaluated using:
   - Accuracy score
   - Confusion Matrix
8. **Plotted** decision boundaries (optional for 2D data).

---

## 🔍 Results
- Best accuracy achieved at `K = 10` 
- Final model accuracy: 1.0
- Confusion matrix plotted to analyze predictions.

---

## 📈 Accuracy vs K Plot
_Example:_

![Accuracy vs K](images/accuracy_vs_k.png)

---

## 📤 Submission
- Code: `knn_classifier.ipynb`
- Report: `README.md`
- Optional: `images/`, `outputs/`

---



