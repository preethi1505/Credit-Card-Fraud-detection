Credit Card Fraud Detection Project
This project implements an AI-powered system to detect fraudulent credit card transactions using machine learning. It identifies unusual patterns in transaction data to flag suspicious activities, helping to prevent financial losses.

Project Overview
The core idea is to build a classification model that distinguishes between legitimate and fraudulent transactions. The process involves:

Data Description: Understanding the raw transaction data.
Data Preprocessing: Cleaning and preparing data for the model.
Exploratory Data Analysis (EDA): Visualizing data to find patterns.
Feature Engineering: Creating new features to improve detection.
Model Building: Training a machine learning model.
Model Evaluation: Assessing the model's performance.
Dataset
The project uses the CreditCard_Fraud_Detection.csv dataset, which contains anonymized transaction features (V1-V28), transaction Amount, Time, and an Is Fraud column as the target variable (0 for legitimate, 1 for fraud). The dataset is highly imbalanced, meaning fraud cases are very rare.

Key Technologies
Python: The primary programming language.
Pandas: For data manipulation and analysis.
Scikit-learn: For machine learning models, data preprocessing (scaling, encoding), and evaluation.
Matplotlib & Seaborn: For data visualization.
How to Run the Code
Prerequisites: Ensure you have Python 3.x installed.
Install Libraries:
Bash

pip install pandas numpy scikit-learn matplotlib seaborn
Dataset: Place the CreditCard_Fraud_Detection.csv file in the same directory as your Jupyter Notebook (NM_Project.ipynb).
Run Jupyter Notebook:
Bash

jupyter notebook
Open NM_Project.ipynb in your browser and run all cells sequentially.
Project Structure (Conceptual)
The NM_Project.ipynb notebook guides you through the following steps:

Dataset Loading & Initial Inspection: Displays basic info, shape, and head of the dataset.
Data Cleaning & Preparation: Handles missing values and prepares features.
Feature Engineering: Creates new features like Hour, Amount_x_Vn, and Amount^2.
Model Training: Trains a GaussianNB classifier.
Evaluation: Provides classification report, confusion matrix, and ROC curve to evaluate performance.
