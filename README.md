# Student Performance Prediction

This project predicts student final grades using machine learning.

## Problem Statement
The goal of this project is to analyze factors affecting student performance and predict the final grade (G3) using machine learning models.

## Dataset
The dataset contains information about students such as:

- Study time
- Absences
- Parental education
- Internet access
- Past academic performance

Target variable: **G3 (final grade)**

## Data Preprocessing
- Removed features G1 and G2 to avoid data leakage
- Converted categorical variables using one-hot encoding
- Performed exploratory data analysis

## Models Used
- Linear Regression
- Random Forest Regressor

## Evaluation Metrics
- R² Score
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)

## Results
Random Forest performed better than Linear Regression in predicting student grades.

## Key Insights
- Study time positively impacts grades
- Higher absences tend to reduce performance
- Previous failures strongly affect final grades

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Project Structure