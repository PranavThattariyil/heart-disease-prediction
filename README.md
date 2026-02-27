# Heart Disease Prediction System

## Overview
A machine learning system that predicts the likelihood of heart disease in patients based on clinical and demographic data. This project compares the performance of Logistic Regression, Random Forest, and XGBoost models to identify the most effective approach for clinical decision support.

## Key Results
- **XGBoost achieved 89.5% accuracy** and an **AUC-ROC of 0.94**
- Random Forest achieved 86.7% accuracy with AUC-ROC of 0.92
- Logistic Regression achieved 81.3% accuracy with AUC-ROC of 0.85
- XGBoost identified **number of major vessels, chest pain type, and ST slope** as the most influential risk factors

## Technologies Used
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn
- **Interpretability:** SHAP, LIME
- **Environment:** Jupyter Notebook, Google Colab

## Dataset
- **Source:** UCI Heart Disease Dataset
- **Features:** Age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, resting ECG, max heart rate, exercise induced angina, ST depression, ST slope, number of major vessels, thalassemia
- **Target:** Presence or absence of heart disease (binary classification)

## Project Structure
- Data cleaning and missing value imputation
- Exploratory Data Analysis (EDA) with visualisations
- Feature scaling using Min-Max normalisation
- Class imbalance handling using SMOTE
- Model training — Logistic Regression, Random Forest, XGBoost
- Hyperparameter tuning using Grid Search Cross Validation
- Model evaluation — Accuracy, Precision, Recall, F1-Score, AUC-ROC, Confusion Matrix
- 5-fold Cross Validation
- Post-hoc interpretability using SHAP and LIME

## How to Run
1. Clone the repository
2. Install the required libraries using pip install -r requirements.txt
3. Open the Jupyter notebook and run all cells

## Author
**Pranav Thattariyil**
- LinkedIn: linkedin.com/in/pranav-thattariyil
- GitHub: github.com/PranavThattariyil
- Email: pranavt0002@gmail.com
