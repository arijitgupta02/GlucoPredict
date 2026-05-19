# Diabetes Prediction using Machine Learning

## Overview

This project focuses on predicting the likelihood of diabetes using Machine Learning techniques and medical diagnostic data. The model analyzes important health-related features such as glucose level, blood pressure, insulin, BMI, and age to determine whether a patient is diabetic or non-diabetic.

The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and prediction using Python and Scikit-learn.

---

## Objectives

- Analyze diabetes related medical data
- Perform data preprocessing and cleaning
- Build a machine learning model for diabetes prediction
- Evaluate model performance using classification metrics
- Predict diabetes risk based on patient health parameters

---

## Dataset

Dataset Used:
- "akshaydattatraykhare/diabetes-dataset"

Dataset Features:
- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

Target Variable:
- Outcome
  - 0 = Non-Diabetic
  - 1 = Diabetic

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Data Preprocessing
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Diabetes Prediction

---

## Exploratory Data Analysis

The project includes:
- Correlation Heatmap
- Feature Distribution Analysis
- Outcome Distribution
- Statistical Data Analysis
- Relationship Analysis between Features

---

## Machine Learning Model

The project uses classification algorithms for diabetes prediction after:
- Handling missing or invalid values
- Scaling numerical features
- Splitting training and testing datasets

The trained model predicts whether a patient is diabetic based on medical parameters.

---

## Evaluation Metrics

Model performance is evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report

---

## Project Structure

```text
diabetes-prediction/
│
├── diabetes_prediction.ipynb
├── README.md
├── requirements.txt
└── data/
    └── diabetes.csv
```

---

## Requirements

```txt
pandas
numpy
matplotlib
seaborn
scikit-learn
```

---

## Run the Project

Open Jupyter Notebook:

```bash
jupyter notebook
```

Run:

```text
GlucoPredict.ipynb
```

---

## Results

The machine learning model successfully predicts diabetes risk using patient medical data and provides insights into the most influential health parameters affecting diabetes prediction.

---

## Applications

- Early Diabetes Risk Detection
- Medical Decision Support Systems
- Healthcare Data Analysis
- Predictive Healthcare Applications
- Clinical Risk Assessment

---

## Future Improvements

- Compare multiple machine learning models
- Perform hyperparameter tuning
- Deploy using Streamlit or Flask
- Add explainable AI techniques
- Build a real-time prediction system

---

## Author

Arijit Gupta
