## SHIFT_ML
# Price forecast for apartments, flats, and houses in the Moscow region
# Deep Palch Learning Team ML Project

## Introduction

This project was carried out as part of the classical machine learning competition organized by SHIFT Lab. The main objective of the project is to build and train a machine learning model for prediction based on the provided data. This notebook documents the process from data exploration and preprocessing to model training and evaluation.

## Project Description

### Libraries Used

- `catboost`
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

### Workflow

1. **Data Preparation**:
    - Loaded the dataset using `pandas`.
    - Conducted exploratory data analysis (EDA) to understand the data distribution and relationships.
    - Preprocessed the data by handling missing values, encoding categorical features, and normalizing numerical features.

2. **Model Building**:
    - Utilized `CatBoostRegressor` for the regression task.
    - Performed hyperparameter tuning using `GridSearchCV` to optimize the model.

3. **Evaluation**:
    - Evaluated the model's performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared score (R2).
    - Visualized model performance and residuals to gain insights into model accuracy and areas of improvement.

## Notebook Structure

- **Library Installation**: Ensuring all necessary libraries are installed.
- **Library Import**: Importing essential libraries for data manipulation, visualization, and model building.
- **Data Loading and Preprocessing**: Loading data, performing EDA, and preprocessing.
- **Model Training**: Training the `CatBoostRegressor` model and tuning hyperparameters.
- **Model Evaluation**: Evaluating and visualizing the model's performance.

## Repository Structure

- `Submission.ipynb` - The main Jupyter Notebook containing code and outputs.
- `EDA.ipynb` -  Jupyter Notebook containing data analisys.
