# 🌸 Iris Flower Classification - Machine Learning Project

This project is part of my Data Science Internship. It uses the **Iris flower dataset** to build a classification model that predicts the species of an iris flower based on its measurements.

---
## Open Collab
https://colab.research.google.com/drive/1XtPExaOYjxO86GFOdk4TVmZzcM0ENVb3?usp=sharing
---
---
## 📌 Objective

> Train a machine learning model using sepal and petal measurements to classify iris flowers into one of three species:
- Setosa
- Versicolor
- Virginica

---

## 📂 Dataset

- **Source**: `iris.csv` (uploaded manually)
- **Features**:
  - `sepal_length`
  - `sepal_width`
  - `petal_length`
  - `petal_width`
- **Target**:
  - `species` (Setosa, Versicolor, Virginica)

---

## ⚙️ Tools & Libraries

- Python
- Pandas, Seaborn, Matplotlib
- scikit-learn (RandomForestClassifier)

---

## 🧪 Steps Performed

1. **Loaded the dataset** from CSV
2. **Exploratory Data Analysis (EDA)** with pairplots
3. **Preprocessed** data (separated features and target)
4. **Split** into training and testing sets (80/20)
5. **Trained** a Random Forest Classifier
6. **Evaluated** the model using accuracy, classification report, and confusion matrix
7. **Predicted** new flower species based on input features

---

## 📊 Model Performance

| Metric          | Value (Example) |
|-----------------|-----------------|
| Accuracy        | 100%            |
| Precision/Recall| Excellent       |
| Confusion Matrix| Minimal errors  |

---

## 🔮 Predicting a New Flower

Example:
```python
Input: [5.1, 3.5, 1.4, 0.2]
Output: setosa
