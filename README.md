# 🍷 Wine Quality Prediction using Machine Learning

Predict wine quality based on physicochemical properties using Machine Learning models and data analysis techniques.

---

## 📖 Overview

Wine quality is influenced by several chemical properties such as acidity, alcohol content, pH, sulphates, and density. This project analyzes these features and builds machine learning models to predict wine quality.

### Objectives

* Perform Exploratory Data Analysis (EDA)
* Visualize feature relationships
* Build and compare ML models
* Predict wine quality scores
* Identify the most influential features

---

## 📊 Dataset

The project uses the Wine Quality Dataset from the UCI Machine Learning Repository.

### Features

| Feature              | Description                        |
| -------------------- | ---------------------------------- |
| Fixed Acidity        | Non-volatile acids                 |
| Volatile Acidity     | Acetic acid concentration          |
| Citric Acid          | Citric acid content                |
| Residual Sugar       | Remaining sugar after fermentation |
| Chlorides            | Salt concentration                 |
| Free Sulfur Dioxide  | Free SO₂                           |
| Total Sulfur Dioxide | Total SO₂                          |
| Density              | Wine density                       |
| pH                   | Acidity level                      |
| Sulphates            | Sulphate concentration             |
| Alcohol              | Alcohol percentage                 |

**Target:** Quality Score (0–10)

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## 🔄 Workflow

```text
Data Collection
      ↓
Data Cleaning
      ↓
EDA
      ↓
Feature Engineering
      ↓
Train/Test Split
      ↓
Model Training
      ↓
Evaluation
```

---

## 📈 Exploratory Data Analysis

### Quality Distribution

![Quality Distribution](images/quality_distribution.png)

### Correlation Heatmap

![Heatmap](images/heatmap.png)

### Feature Analysis

![Feature Analysis](images/feature_analysis.png)

---

## 🤖 Models Used

* Logistic Regression
* Decision Tree
* Random Forest
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)

---

## 📊 Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | XX%      |
| Decision Tree       | XX%      |
| Random Forest       | XX%      |
| SVM                 | XX%      |

> Replace XX with your actual results.

---

## 🔍 Key Findings

* Alcohol content positively impacts wine quality.
* Volatile acidity negatively affects quality.
* Sulphates show a positive correlation with quality.
* Random Forest produced the best overall performance.

---

## 📁 Project Structure

```text
Wine-Quality-check-AI-Model/
│
├── data/
├── notebooks/
├── images/
├── models/
├── README.md
└── requirements.txt
```

---

## 🚀 Installation

```bash
git clone https://github.com/neel1202/Wine-Quality-check-AI-Model-.git
cd Wine-Quality-check-AI-Model-
pip install -r requirements.txt
```

---

## 👨‍💻 Author

Neel Shah

If you found this project useful, give it a ⭐ on GitHub.
