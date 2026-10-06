# Heart Disease Prediction using Machine Learning

## Project Overview

This project uses machine learning to predict whether a person is likely to have **heart disease** based on various health and clinical features.

The project covers data preprocessing, exploratory data analysis, feature transformation, model training, model comparison, evaluation, and model deployment.

## Objective

To build a machine learning classification model that can predict the presence or absence of heart disease based on patient health-related information.

- `0` → No Heart Disease
- `1` → Heart Disease

## Dataset

The project uses the **Heart Disease UCI Dataset**.

- **Records:** 303
- **Features:** 13
- **Target:** HeartDisease
- **Problem Type:** Binary Classification

The dataset contains health and clinical attributes such as age, gender, chest pain type, blood pressure, cholesterol, maximum heart rate, exercise-induced angina, and other medical indicators.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Streamlit
- Pickle

## Project Workflow

### 1. Data Preprocessing

The dataset was prepared for machine learning by:

- Checking and handling duplicate records
- Analyzing missing values
- Identifying and handling outliers
- Encoding categorical features
- Scaling numerical features

### 2. Exploratory Data Analysis

Exploratory analysis was performed to understand the dataset and identify relationships between the health-related features and the target variable.

Visualizations such as distribution plots, box plots, and a correlation heatmap were used for analysis.

### 3. Model Training

Two classification algorithms were trained and compared:

- Logistic Regression
- Random Forest

The models were evaluated using classification metrics and confusion matrices.

### 4. Model Selection

The **Random Forest Classifier** was selected as the final model based on the model comparison performed in the project.

The trained model and required preprocessing components were saved for later use.

## Model Deployment

The trained model was prepared for deployment using **Streamlit**.

The application allows users to enter patient-related information and receive a prediction indicating whether heart disease is likely to be present.

## 👩‍💻 Author

**Iqra Shaikh**

Data Science | Data Analytics | AI/ML
