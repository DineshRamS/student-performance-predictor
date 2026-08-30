# Student Performance Predictor

## Project Overview

This project uses machine learning to predict student performance based on academic and classroom-related factors.

The project compares Linear Regression and Random Forest Regressor models and evaluates their performance using MAE, MSE, and R² Score.

## Features Used

- Weekly Study Hours
- Attendance
- Reading
- Notes
- Listening in Class
- Project Work

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- Jupyter Notebook

## Machine Learning Models

### 1. Linear Regression

Used as the basic regression model for predicting student grades.

### 2. Random Forest Regressor

Used as a second model and compared with Linear Regression.

## Data Preprocessing

The project includes:

- Handling missing values
- Converting categorical variables into numerical values
- Converting grades into numerical values
- Feature selection
- Train-test splitting

## Model Evaluation

| Model | MAE | MSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | 2.15 | 6.99 | -0.13 |
| Random Forest | 2.02 | 5.70 | 0.08 |

Random Forest performed better than Linear Regression on the test dataset based on all three evaluation metrics.

## Feature Importance

The Random Forest model identified the following features as important:

1. Weekly Study Hours
2. Attendance
3. Project Work
4. Listening in Class
5. Notes
6. Reading

## Project Outputs

- `Student_performance_prediction.ipynb` — Complete project notebook
- `cleaned_student_performance.csv` — Cleaned dataset
- `model_evaluation_metrics.csv` — Model evaluation results
- `student_performance_predictions.csv` — Actual and predicted grades
- `feature_importance.csv` — Feature importance results

## Conclusion

The project demonstrates a complete machine learning workflow, including data preprocessing, feature engineering, model training, prediction, evaluation, model comparison, and feature-importance analysis.

Random Forest performed better than Linear Regression, although the R² score indicates that the selected features have limited predictive power for the target grades.
