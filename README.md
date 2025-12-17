# Car Price Prediction Using Machine Learning

## Problem Statement
The objective of this project is to predict the prices of used cars based on various features such as **model**, **year**, **mileage**, **fuel type**, **transmission**, and **engine size** using supervised machine learning techniques.

## Dataset Description
The dataset consists of information about used cars and includes both **numerical** and **categorical** features.  
- **Input features:** model, year, mileage, fuel type, transmission, engine size, etc.  
- **Target variable:** price

## Exploratory Data Analysis (EDA)
Exploratory Data Analysis was performed to gain insights into the dataset:
- Analyzed data distribution and summary statistics  
- Checked and handled missing values  
- Studied correlations between numerical features  
- Examined the impact of **mileage**, **year**, and **engine size** on car prices  

## Data Preprocessing
The following preprocessing steps were applied:
- Handled missing values  
- Encoded categorical variables using **One-Hot Encoding** and **Label Encoding**  
- Scaled numerical features using **StandardScaler**  
- Split the dataset into **training** and **testing** sets  

## Model Building and Evaluation
A supervised machine learning model was trained on the processed data.
- **Evaluation metric:** R² score  
- **Test R² score:** **0.82**

This result indicates that the model has strong explanatory power and can effectively predict car prices based on the given features.

## Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

## Conclusion
The model demonstrates good performance in predicting car prices and can be further improved by feature engineering, hyperparameter tuning, or trying advanced models.
