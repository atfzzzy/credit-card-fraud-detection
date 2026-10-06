# Credit Card Fraud Detection

## Project Overview

A machine learning project that classifies credit card transactions as normal or fraudulent using Logistic Regression.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab

## Project Workflow

1. Loaded and explored the transaction dataset.
2. Checked for missing values and analyzed class distribution.
3. Visualized normal and fraudulent transactions.
4. Addressed class imbalance using random under-sampling.
5. Split the data into training and testing sets.
6. Standardized features using `StandardScaler`.
7. Trained a Logistic Regression model.
8. Evaluated performance using accuracy, precision, recall, F1-score, a confusion matrix, and ROC-AUC.

## Model Evaluation

The notebook reports the model's performance using classification metrics and ROC-AUC.

## How to Run

1. Download or obtain the credit card transaction dataset.
2. Open `Credit_Card_Fraud_Detection.ipynb` in Google Colab.
3. Upload the dataset using the filename and path expected by the notebook.
4. Run the cells from top to bottom.

## Dataset

The dataset contains transaction features and a `Class` label, where `0` represents a normal transaction and `1` represents a fraudulent transaction.

Random under-sampling is used to create a balanced dataset for model training.


