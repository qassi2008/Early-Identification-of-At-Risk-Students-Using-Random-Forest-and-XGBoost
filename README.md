# Project Overview
The goal of this project is to develop and compare machine learning models (Random Forest and XGBoost) to predict student performance based on a dataset of student information, including demographic, academic, and socio-economic factors. This approach allows for the early identification of students at risk of failing, helping educational institutions to take action.

## Dataset
The dataset used in this project was sourced from the UCI Machine Learning Repository, containing student performance data from Portuguese secondary schools. It includes features such as:
- Demographic information
- Family background
- Academic performance (grades)
- Social and behavioral factors
 
The dataset contains information on both Mathematics and Portuguese courses, which serve as the target variables.

## Features
- Data Preprocessing: Data cleaning, feature engineering (e.g., attendance rate, parental involvement), and scaling.
- Model Training: Hyperparameter tuning using GridSearchCV for both Random Forest and XGBoost models.
- Evaluation Metrics: The models were evaluated using accuracy, precision, recall, and F1-scores.

## Setup and Installation
Prerequisites
Make sure you have the following installed:

- Python 3.6+
- Jupyter Notebook
- Required Python libraries: scikit-learn, xgboost, pandas, numpy, matplotlib

## Results
The models were evaluated using multiple metrics. XGBoost demonstrated superior performance, especially in handling complex feature interactions. Below are the results for both models:

## Random Forest:
- Accuracy (Mathematics): 88%
- Accuracy (Portuguese): 92%

  
## XGBoost:
- Accuracy (Mathematics): 89%
- Accuracy (Portuguese): 91%
Both models proved effective in identifying at-risk students, with XGBoost performing slightly better due to its ability to capture more complex data patterns.

## Future Work
Future improvements may include:

- Integrating temporal data to track student performance over time.
- Exploring deep learning techniques for better performance on larger datasets.
- Developing a web-based interface for educators to visualize and interact with the model outputs.
