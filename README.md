# Predicting client churn using Supervised Classification models

This repository contains Python code for a machine learning project focused on predicting client churn for a credit company. 
The objective is to identify customers who are likely to leave, enabling the company to take preventive actions.

## Project Overview

In this project, I implemented five different classification models to predict client churn using a structured dataset. The 
models used are:

1. **Logistic Regression**
2. **Random Forest Classifier**
3. **Support Vector Machine**
4. **Gaussian Naive Bayes**
5. **K-Nearest Neighbors Classifier**

Each model has been evaluated based on metrics ROC AUC metrics to determine its 
performance. This comparison helps in selecting the most suitable model for deployment in a production environment.

## Features

- Data preprocessing steps, including handling missing values and feature scaling.
- Implementation of multiple machine learning classification algorithms.
- Model evaluation with metrics for performance comparison.
- Code structured to facilitate future updates and model improvements.

## How to Use

1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```
3. Run the EDA notebook first, and then the modelling notebook to train and evaluate the models.
