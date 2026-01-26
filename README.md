Heart Disease Prediction using Machine Learning

Project Overview

This project aims to predict the presence of heart disease using clinical and demographic patient data. The dataset includes medical attributes such as age, cholesterol level, blood pressure, and heart rate.

Objective

The objective of this project is to build an accurate and interpretable machine learning model that can predict whether a patient has heart disease using supervised learning techniques.

Dataset
 • Source: Kaggle – Heart Disease Dataset
 • Number of records: 1,025 patients
 • Number of features: 14 medical and demographic attributes
 • Target variable:
 • 1 indicates the presence of heart disease
 • 0 indicates no heart disease

Methodology
 • Data cleaning and preprocessing
 • Handling missing values
 • Feature standardization using StandardScaler
 • Splitting the dataset into training (75%) and testing (25%) sets
 • Training a Logistic Regression model with balanced class weights

Model
 • Algorithm: Logistic Regression
 • Library used: scikit-learn
 • Evaluation metrics:
 • Accuracy
 • Precision
 • Recall
 • F1-score
 • Confusion Matrix

Results
 • The model achieved approximately 83% accuracy
 • Performance was balanced across both classes
 • The model demonstrates good interpretability, making it suitable for healthcare-related applications

Tools and Technologies
 • Python
 • Pandas
 • NumPy
 • Scikit-learn
 • Matplotlib
 • Seaborn
 • Jupyter Notebook

Files in This Repository
 • heart_disease_analysis.ipynb: Jupyter notebook containing the full implementation
 • report.pdf: Detailed project report
 • README.md: Project documentation

Author

Albatul Altoum