# Titanic-Survival-Prediction

This project implements a Machine Learning solution for the classic Titanic: Machine Learning from Disaster competition on Kaggle. It utilizes the Random Forest algorithm to predict passenger survival based on various features such as age, gender, and socio-economic status.

## Project Overview
The objective is to perform exploratory data analysis (EDA), feature engineering, and predictive modeling on the Titanic dataset. The workflow includes handling missing values, categorical encoding, and fine-tuning a Random Forest Classifier.

## Key Features
- Feature Engineering: Extracting titles from names and calculating family sizes.
- Data Imputation: Handling missing values in Age, Fare, and Embarked columns.
- Categorical Encoding: Using One-Hot Encoding for categorical variables.
- Model Selection: Implementing a Random Forest Classifier with 300 estimators.

## Tech Stack
- Python
- Pandas & NumPy (Data Processing)
- Scikit-learn (Machine Learning)

## Model Performance
The Random Forest model is configured with a maximum depth of 6 and minimum sample splits to ensure generalization and prevent overfitting on the training data.

## Dataset
The project uses the standard Titanic competition dataset from Kaggle, consisting of:
- train.csv: Data used to train the model.
- test.csv: Data used to generate survival predictions.
