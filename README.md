Wine-Quality-check-AI-Model
🍷 Wine Quality Analysis and Prediction using Machine Learning
Overview

This project focuses on analyzing and predicting wine quality using Machine Learning techniques. The dataset contains physicochemical properties of red and white Portuguese "Vinho Verde" wines along with their quality ratings assigned by wine experts.

The objective is to explore the factors affecting wine quality, perform detailed Exploratory Data Analysis (EDA), and build predictive models capable of estimating wine quality scores or classifying wines into quality categories.

This project demonstrates the complete Machine Learning workflow, including:

Data Collection
Data Cleaning and Preprocessing
Exploratory Data Analysis (EDA)
Feature Engineering
Model Training
Model Evaluation
Performance Comparison
📂 Dataset

The dataset used in this project is the famous Wine Quality Dataset from the UCI Machine Learning Repository.

Dataset Files
winequality-red.csv
winequality-white.csv
Features

The dataset contains the following physicochemical attributes:

Feature	Description
Fixed Acidity	Concentration of non-volatile acids
Volatile Acidity	Amount of acetic acid present
Citric Acid	Citric acid content
Residual Sugar	Sugar remaining after fermentation
Chlorides	Salt concentration
Free Sulfur Dioxide	Free SO₂ content
Total Sulfur Dioxide	Total SO₂ content
Density	Density of wine
pH	Acidity/alkalinity level
Sulphates	Potassium sulphate content
Alcohol	Alcohol percentage
Target Variable
Variable	Description
Quality	Wine quality score (0–10)
🎯 Project Objectives
1. Exploratory Data Analysis (EDA)

Perform comprehensive data analysis to:

Understand feature distributions
Detect missing values and outliers
Analyze correlations between variables
Study relationships between wine characteristics and quality
Compare red and white wine properties
2. Data Visualization

Generate visual insights using:

Histograms
Box Plots
Heatmaps
Correlation Matrices
Pair Plots
Scatter Plots
Quality Distribution Charts
3. Data Preprocessing

Prepare the dataset for machine learning by:

Handling missing values
Removing duplicates
Detecting and treating outliers
Feature scaling and normalization
Feature selection
Train-test splitting
4. Regression Modeling

Predict the exact wine quality score using regression algorithms:

Linear Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
5. Classification Modeling

Categorize wines into quality classes such as:

Category	Quality Range
Low	0 – 4
Medium	5 – 6
High	7 – 10

Algorithms used:

Logistic Regression
Decision Tree Classifier
Random Forest Classifier
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)
📊 Exploratory Data Analysis

EDA helps uncover important patterns within the dataset.

Key analyses include:

Quality Distribution
Frequency of quality scores
Class imbalance analysis
Feature Correlation
Correlation heatmaps
Identification of highly correlated variables
Alcohol vs Quality

Analyze how alcohol content influences wine quality ratings.

Acidity Analysis

Study the impact of:

Fixed Acidity
Volatile Acidity
Citric Acid

on wine quality.

Outlier Detection

Identify unusual observations using:

Box plots
Interquartile Range (IQR)
🤖 Machine Learning Workflow
Step 1: Data Loading
import pandas as pd

df = pd.read_csv("winequality-red.csv")
Step 2: Data Cleaning
Remove duplicates
Handle missing values
Verify data types
Step 3: Feature Engineering
Create quality categories
Normalize numerical features
Step 4: Train-Test Split
from sklearn.model_selection import train_test_split

X_train, X_test, y_train, y_test = train_test_split(
    X, y,
    test_size=0.2,
    random_state=42
)
Step 5: Model Training

Train multiple models and compare performance.

Step 6: Model Evaluation

Evaluate using appropriate metrics.

📈 Evaluation Metrics
Regression Metrics
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R² Score
Classification Metrics
Accuracy
Precision
Recall
F1-Score
Confusion Matrix
ROC-AUC Score
🛠️ Technologies Used
Programming Language
Python 3.x
Data Manipulation
Pandas
NumPy
Data Visualization
Matplotlib
Seaborn
Machine Learning
Scikit-learn
Development Environment
Jupyter Notebook
Google Colab
VS Code
📁 Project Structure
Wine-Quality-check-AI-Model/
│
├── data/
│   ├── winequality-red.csv
│   └── winequality-white.csv
│
├── notebooks/
│   └── wine_quality_analysis.ipynb
│
├── models/
│   └── trained_models.pkl
│
├── images/
│   ├── correlation_heatmap.png
│   ├── quality_distribution.png
│   └── feature_analysis.png
│
├── requirements.txt
├── README.md
└── LICENSE
🔍 Key Insights

Some commonly observed findings include:

Higher alcohol content often correlates with better wine quality.
Volatile acidity generally shows a negative correlation with quality.
Sulphates can positively influence wine quality.
Quality scores are not uniformly distributed and often suffer from class imbalance.
Random Forest models typically outperform simpler baseline models.
🚀 Future Improvements
Hyperparameter tuning using GridSearchCV
Cross-validation for robust evaluation
Deep Learning models using TensorFlow/Keras
Model deployment with Flask or FastAPI
Interactive dashboard using Streamlit
Real-time wine quality prediction system
📚 References
UCI Machine Learning Repository
Scikit-learn
Pandas
NumPy
Matplotlib
Seaborn
👨‍💻 Author

Neel Shah
