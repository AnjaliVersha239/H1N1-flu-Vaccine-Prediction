# H1N1-flu-Vaccine-Prediction
Project Overview

This project focuses on predicting whether an individual is likely to take the H1N1 vaccine and the Seasonal Flu vaccine using demographic, behavioral, and opinion-based survey data.

The goal is to build machine learning models that can identify patterns influencing vaccination behavior. This analysis helps understand public health trends and can assist policymakers in improving vaccination campaigns.

# Problem Statement

Vaccination plays a critical role in preventing infectious diseases. However, many individuals choose not to get vaccinated due to various reasons such as lack of awareness, mistrust, or perceived risk.

This project aims to:

- Analyze survey data related to vaccination behavior.

- Identify key factors influencing vaccine uptake.

- Build predictive models to determine whether a person is likely to take the vaccine.

# Dataset Description

- The dataset contains survey responses regarding:

- Demographic information

- Health-related behaviors

- Risk perception

- Opinions about vaccines

- Healthcare accessibility

- Vaccination status

#  Target Variables

h1n1_vaccine – Whether the respondent took the H1N1 vaccine

seasonal_vaccine – Whether the respondent took the seasonal flu vaccine

# Feature Categories

The dataset includes multiple types of features:

# 1. Demographic Features

- Age group

- Education

- Income level

- Marital status

- Employment status

# 2. Behavioral Features

- Use of preventive measures

- Doctor recommendations

- Health insurance status

# 3. Opinion-Based Features

- Concern about H1N1

- Perceived vaccine effectiveness

- Perceived risk of illness

# 4. Healthcare Access

- Doctor visits

- Access to healthcare services

# Data Preprocessing

- Several preprocessing steps were performed to prepare the data for modeling:

- Handling missing values

- Encoding categorical variables

- Feature scaling where necessary

- Exploratory Data Analysis (EDA)

- Train-test data splitting

# Missing Value Analysis

- Some categorical variables had high missing rates such as:

- employment_industry

- employment_occupation

- income_poverty

- rent_or_own

- marital_status

Appropriate strategies were used to handle these missing values.

# Exploratory Data Analysis

EDA was performed to understand relationships between features and vaccination behavior.

Key insights include:

- Individuals with higher concern about H1N1 were significantly more likely to take the vaccine.

- Doctor recommendations strongly influenced vaccine uptake.

- Higher perceived vaccine effectiveness increased the likelihood of vaccination.

- Education level and income also showed moderate correlations with vaccination decisions.

Visualizations were used to analyze:

- Vaccine uptake by concern level

- Vaccine uptake by opinion scores

- Demographic patterns

- Distribution of key features

# Machine Learning Models

Multiple machine learning models were implemented and compared.

# Models Used

- Logistic Regression

- Decision Tree

- Random Forest

- XGBoost

- Multi-Layer Perceptron (Neural Network)

Each model was evaluated using consistent preprocessing and train-test splits to ensure fair comparison.

# Model Evaluation Metrics

The models were evaluated using:

- Accuracy

- Precision

- Recall

- F1 Score

- ROC-AUC Score

- Confusion Matrix

These metrics help assess both classification performance and model reliability.

# Results

Among all models tested:

- XGBoost and Random Forest delivered the best performance.

- Ensemble methods captured complex feature interactions better than simple models.

- Logistic Regression provided strong baseline performance with good interpretability.

The best-performing model showed strong predictive capability in identifying individuals likely to receive vaccines.

# Project Structure
Vaccine-Prediction-Project
│
├── PRCP-1014-VaccinePred_final.ipynb
├── README.md
└── dataset

# Technologies Used

- Python

- Pandas

- NumPy

- Matplotlib

- Seaborn

- Scikit-learn

- XGBoost

- Jupyter Notebook

# How to Run the Project
# 1. Clone the Repository
git clone https://github.com/AnjaliVersha239/H1N1-flu-Vaccine-Prediction
# 2. Install Required Libraries
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
# 3. Run the Notebook

Open the notebook in Jupyter:

jupyter notebook PRCP-1014-VaccinePred_final.ipynb

# Key Takeaways

- Public perception and concern about diseases significantly influence vaccination behavior.

- Doctor recommendations play a crucial role in vaccine acceptance.

- Machine learning models can effectively predict vaccination decisions using survey data.

# Future Improvements

Possible improvements for the project include:

- Hyperparameter optimization

- Feature engineering

- Model explainability using SHAP or LIME

- Deployment as a web application

- Real-time vaccination prediction dashboard
