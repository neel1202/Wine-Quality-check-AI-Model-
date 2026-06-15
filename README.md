# 🍷 Wine Quality Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Overview

This project focuses on predicting wine quality using Machine Learning techniques. By analyzing physicochemical properties such as acidity, alcohol content, pH, sulphates, and density, the model learns patterns that influence wine quality ratings.

The project includes data preprocessing, exploratory data analysis (EDA), visualization, feature engineering, model training, and performance evaluation.

---

## 📊 Dataset

The dataset contains physicochemical properties of red and white wines along with their quality scores.

### Features

* Fixed Acidity
* Volatile Acidity
* Citric Acid
* Residual Sugar
* Chlorides
* Free Sulfur Dioxide
* Total Sulfur Dioxide
* Density
* pH
* Sulphates
* Alcohol

### Target Variable

* Quality Score (0–10)

---

## 🚀 Project Workflow

```text
Wine Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Feature Engineering
      │
      ▼
Train-Test Split
      │
      ▼
Model Training
      │
      ▼
Model Evaluation
```

---

## 🛠️ Technologies Used

| Category                | Tools               |
| ----------------------- | ------------------- |
| Programming Language    | Python              |
| Data Analysis           | Pandas, NumPy       |
| Visualization           | Matplotlib, Seaborn |
| Machine Learning        | Scikit-Learn        |
| Development Environment | Jupyter Notebook    |

---

## 🔍 Exploratory Data Analysis

The following analyses were performed:

* Quality distribution analysis
* Correlation heatmap
* Feature importance study
* Outlier detection
* Relationship between alcohol content and quality
* Acidity analysis

---

## 🤖 Machine Learning Models

### Regression Models

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

### Classification Models

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Random Forest Classifier

---

## 📈 Evaluation Metrics

### Regression

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

### Classification

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 📊 Results

| Model               | Performance  |
| ------------------- | ------------ |
| Logistic Regression | XX% Accuracy |
| Random Forest       | XX% Accuracy |
| SVM                 | XX% Accuracy |
| KNN                 | XX% Accuracy |

> Replace the values above with your actual results.

---

## 🔑 Key Insights

* Higher alcohol content generally leads to better wine quality.
* Volatile acidity negatively affects wine quality.
* Sulphates show a positive correlation with quality.
* Random Forest provided the best performance among tested models.

---

## 📂 Project Structure

```text
Wine-Quality-check-AI-Model/
│
├── Dataset/
│   ├── winequality-red.csv
│   └── winequality-white.csv
│
├── Notebook/
│   └── Wine_Quality_Analysis.ipynb
│
├── Images/
│   ├── heatmap.png
│   ├── quality_distribution.png
│   └── feature_analysis.png
│
├── README.md
└── requirements.txt
```

---

## 📷 Sample Visualizations

Add screenshots of:

* Correlation Heatmap
* Quality Distribution Graph
* Feature Importance Plot
* Confusion Matrix

Example:

```md
![Heatmap](Images/heatmap.png)
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Wine-Quality-check-AI-Model.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

---

## 🌟 Future Improvements

* Hyperparameter tuning
* Deep Learning models
* Streamlit deployment
* Real-time wine quality prediction
* Model explainability using SHAP

---

## 👨‍💻 Author

**Neel Shah**

Machine Learning | Data Science | Python

If you found this project useful, consider giving it a ⭐ on GitHub.
