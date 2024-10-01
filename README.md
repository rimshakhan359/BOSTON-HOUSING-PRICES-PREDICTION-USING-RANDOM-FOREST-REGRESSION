# BOSTON-HOUSING-PRICES-PREDICTION-USING-RANDOM-FOREST-REGRESSION

Boston Housing Price Prediction
Project Overview
This project aims to predict the median value of owner-occupied homes in the Boston area using machine learning techniques. The dataset, known as the Boston Housing dataset, is a classic in the machine learning community and serves as a valuable resource for practicing regression analysis and understanding the relationships between various socioeconomic factors and housing prices.

Objectives
Explore and preprocess the Boston Housing dataset.
Implement multiple regression techniques to predict house prices.
Evaluate model performance using metrics such as R² score.
Gain insights into the factors influencing housing prices.
Dataset
The Boston Housing dataset contains 506 samples and 13 feature variables. Key features include:

CRIM: Per capita crime rate by town.
RM: Average number of rooms per dwelling.
AGE: Proportion of owner-occupied units built prior to 1940.
NOX: Nitric oxides concentration.
DIS: Weighted distances to five Boston employment centers.
TAX: Full-value property tax rate.
The target variable is the median value of owner-occupied homes in thousands of dollars.

Methodology
Data Loading and Preprocessing:

Load the dataset using pandas.
Handle missing values using mean imputation.
Data Splitting:

Split the dataset into training and testing sets (75% train, 25% test).
Model Implementation:

Use the Random Forest Regression model to predict housing prices.
Train the model on the training dataset and make predictions on the test set.
Model Evaluation:

Evaluate model performance using the R² score, providing insights into the model's accuracy.
Single Prediction:

Demonstrate the model's ability to predict a specific house price based on given feature values.
Results
The Random Forest model achieved an impressive R² score, indicating a strong fit to the data and effective predictions of housing prices. The project illustrates the practical application of regression analysis and machine learning techniques in real estate analysis.

Technologies Used
Python
NumPy
Pandas
Matplotlib
scikit-learn
Future Work
Explore hyperparameter tuning to improve model performance.
Experiment with additional regression techniques (e.g., Gradient Boosting).
Deploy the model as a web application for interactive price predictions.
Conclusion
This project provides a comprehensive introduction to machine learning and regression analysis using the Boston Housing dataset. It serves as a foundational step in understanding the dynamics of housing prices and the factors that influence them.
