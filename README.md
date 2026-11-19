# Customer Churn Prediction using Machine Learning

## Project Overview
This project focuses on analyzing customer churn and building Machine Learning classification models to identify customers who are likely to leave a telecom service.

The objective is to understand customer behavior, explore patterns in the dataset, and evaluate different classification algorithms for churn prediction.

## Dataset
The dataset contains customer-related information, including:
- Customer demographics
- Service usage details
- Account information
- Billing-related information
- Churn status

The target variable is `Churn`, which represents whether a customer has churned or not.

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow
1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Missing Value Handling
5. Feature Engineering
6. Data Preprocessing
7. Train-Test Split
8. Model Building
9. Model Evaluation
10. Random Label Sanity Check

## Machine Learning Models
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

## Model Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

## Key Findings
- Exploratory Data Analysis did not reveal strong relationships between the available features and customer churn.
- Logistic Regression achieved the highest recall among the evaluated models.
- Gradient Boosting achieved the highest test AUC.
- Random label experiments showed that the model performance could not be clearly distinguished from random noise.

## Conclusion
The analysis indicates that the available dataset provides very limited predictive information for identifying customer churn.

This project demonstrates an end-to-end Machine Learning workflow, including data cleaning, exploratory analysis, model development, evaluation, and validation using random-label experiments.

## How to Run
1. Clone or download this repository.
2. Open the notebook using Google Colab or Jupyter Notebook.
3. Upload the required dataset.
4. Update the dataset path if necessary.
5. Run all cells in sequence.
