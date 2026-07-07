# Cardiovascular Disease Prediction Using Machine Learning

## Overview
This project uses machine learning to predict whether a person has cardiovascular disease based on clinical and lifestyle risk factors.

The goal is to build a structured-data machine learning pipeline that supports early risk screening and helps identify important factors related to cardiovascular disease.

## Business Problem
Cardiovascular disease is a major health problem worldwide. Early identification of high-risk individuals can support preventive healthcare, improve long-term outcomes, and reduce pressure on healthcare systems.

This project explores whether machine learning can use patient-related features such as age, cholesterol, blood pressure, glucose level, smoking status, alcohol use, physical activity, height, and weight to predict cardiovascular disease risk.

## Problem Type
This is a binary classification problem.

Target classes:
- 0 = No cardiovascular disease
- 1 = Cardiovascular disease

## Dataset
Dataset: Cardiovascular Disease Dataset  
Source: Kaggle  

The dataset contains structured clinical and lifestyle features used to predict the presence or absence of cardiovascular disease.

## Methods
The project includes:

- Data loading and inspection
- Data cleaning
- Feature engineering
- BMI calculation
- Exploratory data analysis
- Model training
- Hyperparameter tuning
- Model evaluation
- Threshold tuning for recall analysis
- Feature importance analysis
- Discussion of limitations and healthcare interpretation

## Models Compared
- Logistic Regression
- Decision Tree
- Random Forest

## Results
The project compares multiple machine learning models and evaluates their performance using classification metrics.

Random Forest was selected as the strongest overall model in the pipeline, especially when considering F1-score and ROC-AUC.

Threshold tuning was also explored to show the trade-off between recall and precision, which is important in healthcare use cases where detecting positive cases can be especially valuable.

## Feature Importance
The project uses feature importance analysis to understand which variables contributed most to the model predictions.

Important risk-related features include:
- Age
- Blood pressure
- BMI
- Cholesterol
- Glucose level

## Tools & Technologies
- Python
- pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
- Logistic Regression
- Decision Tree
- Random Forest
- Model Evaluation
- Feature Importance
- Google Colab / Jupyter Notebook

## Project Structure
cardiovascular-disease-prediction-ml/
├── README.md
├── reports/
│   └── cardiovascular_disease_prediction.html
├── notebooks/
│   └── cardiovascular_disease_prediction.ipynb
├── requirements.txt
├── .gitignore
└── LICENSE

## How to Run
1. Clone the repository.
2. Install the required Python packages.
3. Download the dataset from Kaggle.
4. Open the notebook in Google Colab or Jupyter Notebook.
5. Run the notebook cells in order.

## Limitations
- This project is for learning and portfolio purposes.
- The model should not be used for real medical diagnosis.
- More rigorous validation would be needed before any real healthcare use.
- Healthcare decisions should always involve qualified medical professionals.

## Future Improvements
- Test additional models such as XGBoost or LightGBM
- Add cross-validation
- Improve feature engineering
- Add model explainability using SHAP
- Build a simple dashboard or web app
- Validate the model on another cardiovascular dataset

## Author
Zainab Alzubair  
Data Science, AI, and Digital Marketing student based in Berlin  
LinkedIn: https://www.linkedin.com/in/zainab-alzubair/
