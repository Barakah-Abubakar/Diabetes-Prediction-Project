# Diabetes-Prediction-Project
This project aims to predict diabetes using machine learning with features such as Sex, Age, blood pressure, cholestoerol level, BMI, lifestyle and eating habits.
## Table of Contents
- [Executive Summary](#executive-summary)
- [Project Overview](#project-overview)
- [Tools & Libraries](#tools-&-libraries)
- [Dataset](#dataset)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-(eda))
- [Data Preprocessing](#data-preprocessing)
- [Machine Learning Models Tested](#machine-learning-models-tested)
- [Model Performance](#model-performance)
## Executive Summary
Diabetes remains one of the world’s most challenging public health issues, affecting hundreds of millions of people globally. Early identification of high-risk individuals can reduce complications, improve treatment outcomes, and support preventive health decisions.
This project develops a **machine learning model** that predicts whether an individual is likely to develop diabetes based on diagnostic and physiological features. The project explores data cleaning, feature engineering, model comparison, and evaluation to build a clinically meaningful prediction tool.
## Project Overview
This project applies supervised machine learning techniques to classify individuals as **diabetic** or **non-diabetic** using clinical measurements such as cholestoerol level and BMI

 ## Tools & Libraries
- **Python**  
- **Pandas, NumPy**  
- **Matplotlib, Seaborn** (for visualization)  
- **Scikit-Learn** (modeling)  
- **Google Colab** (development environment)  
- **Streamlit** (planned deployment)

## Dataset
https://www.kaggle.com/datasets/adityarajkaushik1206/diabetes-012-health-indicators-brfss2015
- **source:** kaggle

##  Exploratory Data Analysis (EDA)
- Dashboards showing Relationship between diabetes frequency and cholesterol levels, age, blood pressure and BMI
##  Data Preprocessing
- Split dataset into train/test sets  
- Balanced performance evaluation using accuracy + recall (important for medical predictions)
- Standardized continuous variables using **StandardScaler
- converted categorical values to numerical data using one-hot encoding
##  Machine Learning Models Tested
Models typically compared:
- Logistic Regression  
- Random Forest Classifier  
- Gradient Boosting  
- **Final selected model:** *Gradient Boosting(XG Boost)* 
##  Model Performance  


