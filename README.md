ML-SHIFT: Price Forecast for Apartments, Flats, and Houses in the Moscow Region
Deep Palch Learning Team ML Project
Introduction
This project was carried out as part of the classical machine learning competition organized by SHIFT Lab. The main objective of the project is to build and train a machine learning model for price prediction based on the provided data. This README documents the process from data exploration and preprocessing to model training and evaluation.

Project Description
Libraries Used
catboost
pandas
numpy
scikit-learn
matplotlib
seaborn
Workflow
Data Preparation:
Data Loading: Loaded the dataset using pandas.
Exploratory Data Analysis (EDA): Conducted EDA to understand the data distribution and relationships.
Data Preprocessing:
Handled missing values.
Encoded categorical features.
Normalized numerical features.
Model Building:
Model Selection: Utilized CatBoostRegressor for the regression task.
Hyperparameter Tuning: Performed hyperparameter tuning using GridSearchCV to optimize the model.
Evaluation:
Model Performance: Evaluated the model's performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared score (R2).
Visualization: Visualized model performance and residuals to gain insights into model accuracy and areas of improvement.
Notebook Structure
Library Installation: Ensuring all necessary libraries are installed.
Library Import: Importing essential libraries for data manipulation, visualization, and model building.
Data Loading and Preprocessing: Loading data, performing EDA, and preprocessing.
Model Training: Training the CatBoostRegressor model and tuning hyperparameters.
Model Evaluation: Evaluating and visualizing the model's performance.
Repository Structure
ML-SHIFT Model.ipynb - The main Jupyter Notebook containing code and outputs.
requirements.txt - List of required libraries for the project.
