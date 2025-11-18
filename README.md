# student-outcome-prediction-classifiaction-Student Outcome Prediction – Classification Student Outcome Prediction -- Classification

This project predicts **student outcomes** (such as Pass/Fail or
performance category) using machine learning classification models. The
goal is to analyze student data, clean it, visualize patterns, train
models, and compare their performance.

## ⭐ Objective

To build a machine learning model that can accurately predict student
outcomes based on academic, demographic, and behavioral features.

## 🔧 Models Used

-   **Logistic Regression**
-   **Random Forest Classifier**

## 🗂️ Steps Performed

### 1. Data Cleaning

-   Removed duplicates\
-   Handled missing values\
-   Encoded categorical variables\
-   Normalized numerical features\
-   Outlier removal\
-   Train--Test splitting

### 2. Exploratory Data Analysis (EDA)

-   Correlation heatmap\
-   Feature distributions\
-   Relationship graphs\
-   Boxplots for outlier detection

### 3. Model Training

-   Logistic Regression as baseline\
-   Random Forest for improved accuracy

### 4. Model Evaluation

Metrics used: - Accuracy Score\
- F1-Score\
- Confusion Matrix\
- Classification Report

## 📊 Results (Example)

  Model                 Accuracy   F1-Score
  --------------------- ---------- ----------
  Logistic Regression   0.82       0.79
  Random Forest         0.90       0.88

## 📎 Features Used (Example)

-   Attendance\
-   Study Hours\
-   Previous Scores\
-   Internal Marks\
-   Parental Education\
-   Gender\
-   Final Outcome (Target)

## ▶️ How to Run the Project

### Install dependencies:

    pip install -r requirements.txt

### Run the notebook/script:

    jupyter notebook

or

    python model.py

## 🛠️ Technologies Used

-   Python\
-   Pandas\
-   NumPy\
-   Scikit-learn\
-   Matplotlib\
-   Seaborn





