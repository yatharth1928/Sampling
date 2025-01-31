# Sampling
# Credit Card Fraud Detection with Sampling Techniques

# Overview

This project focuses on detecting credit card fraud using machine learning models. It employs Synthetic Minority Over-sampling Technique (SMOTE) to balance the dataset and various sampling techniques to evaluate model performance.

# Dataset

The dataset used is Creditcard_data.csv, which should contain:

Features representing transaction details

A Class column indicating fraud (1) or non-fraud (0) transactions

# Installation

Ensure you have Python installed along with the necessary libraries. You can install dependencies using:

pip install pandas numpy scikit-learn imbalanced-learn

# Code Functionality

Data Loading: Reads the dataset and checks the class distribution.

Data Balancing: Uses SMOTE to balance the dataset.

Sampling Methods: Applies random and systematic sampling techniques.

Model Training & Evaluation: Trains five classifiers:

Logistic Regression

Decision Tree

Random Forest

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

Performance Comparison: Evaluates models using accuracy scores across different samples.

Result Storage: Saves the accuracy matrix as sampling_results.csv.

# Running the Script

Run the script with:

python script.py

Ensure the dataset is in the same directory or update the file_path variable accordingly.

# Output

Prints accuracy results for different models and sampling techniques.

Saves the accuracy matrix to sampling_results.csv.
