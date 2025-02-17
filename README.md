# 🚢 Titanic - Machine Learning from Disaster  

This repository contains a machine learning project aimed at predicting passenger survival on the Titanic using classification models. It follows data preprocessing, exploratory analysis, and model training techniques to achieve the best results.

## 📂 Dataset  
The dataset is sourced from the [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic). It consists of:  
- **train.csv** – Training data with survival labels  
- **test.csv** – Test data without survival labels  
- **gender_submission.csv** – Sample submission format  

## 📊 Exploratory Data Analysis (EDA)  
- Analyzed survival rates based on different features  
- Visualized data distributions using seaborn/matplotlib  
- Checked and handled missing values  

## 🛠 Data Preprocessing  
- Filled missing values in **Age**, **Embarked**, and **Fare**  
- Encoded categorical features like **Sex** and **Embarked**  
- Extracted titles from passenger names for better feature representation  
- Scaled numerical variables where necessary  

## 🤖 Model Implemented  
- Logistic Regression  

## 📈 Model Evaluation  
- Fine-tuned hyperparameters for better predictions  
- Used cross-validation for model robustness  
