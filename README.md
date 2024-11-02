# Mental Health Risk Prediction

This repository contains my first data science project for **TDS 2101: Fundamental Data Science**. As my introduction to data science, this project explores mental health risk factors among college students, using machine learning classification algorithms to identify significant predictors and compare model performances.

## Project Overview
Mental health issues, including anxiety, depression, and panic attacks, are prevalent among university students who face academic and social pressures. This study, completed in my first data science course, aims to predict mental health risk factors based on demographic and academic data. By comparing various machine learning algorithms, we identify effective predictors and the best-performing model for classifying mental health risks.

## Dataset
The dataset used in this study is from Kaggle, titled **Student Mental Health**. It includes data from 101 university students with variables such as:
- Gender, Age, Course, Year of Study, CGPA, Marital Status
- Mental health indicators (Depression, Anxiety, Panic Attacks)
- Whether the student sought mental health treatment

## Key Steps
1. **Data Preprocessing**: Cleaned and standardized data by handling missing values and irrelevant columns.
2. **Exploratory Data Analysis (EDA)**: Analyzed data distributions and relationships between variables and mental health indicators.
3. **Feature Selection**: Applied chi-squared tests and SelectKBest to select relevant features for mental health predictions.
4. **Model Selection**: Compared the performance of classification algorithms, including logistic regression and k-means clustering.
5. **Hyperparameter Tuning**: Enhanced model performance using GridSearchCV.

## Results
- Logistic Regression achieved the highest accuracy (70%) for predicting mental health risk factors after hyperparameter tuning.
- Key predictors of mental health issues were **Gender, Age, Course, CGPA, and Marital Status**.

## Limitations & Future Work
Due to the small dataset, results may not generalize to a larger population. Future work could involve using larger datasets and additional machine learning techniques to improve predictive power.

## License
This project is for educational purposes as part of coursework for TDS 2101.
