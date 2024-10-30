# ECL Credit Risk Prediction Model
## Overview
This repository contains the code and documentation for an Expected Credit Loss (ECL) Credit Risk Prediction Model built using machine learning. This model predicts the probability of default for loans, supporting financial institutions in assessing credit risk more accurately and efficiently. Achieving an accuracy of 93% and an F1 score of 82%, the model improves on traditional risk assessment metrics by leveraging historical data and advanced predictive techniques.

## Features
Model Accuracy: 93%
F1 Score: 82%
Key Algorithms: Logistic Regression, Random Forest, and Gradient Boosting
Data Handling: Data pre-processing and feature engineering steps for handling missing values, outliers, and categorical encoding
Pipeline: Automated model training pipeline with hyperparameter tuning and model evaluation

## Project Structure
.
├── data/                   # Sample data files and data dictionary
├── notebooks/              # Jupyter notebooks for EDA and model development
├── src/                    # Source code for model pipeline
│   ├── preprocessing.py    # Preprocessing and feature engineering scripts
│   ├── train_model.py      # Model training and evaluation
│   └── predict.py          # Inference script for generating predictions
├── requirements.txt        # Project dependencies
└── README.md               # Project documentation

## Installation
1. Clone the repository
git clone https://github.com/yourusername/ecl-credit-risk-model.git

2. Install the dependencies
pip install -r requirements.txt

## Usage
Data Preprocessing: Use the preprocessing.py script to clean and prepare data.
Model Training: Run train_model.py to train the model using default parameters or your custom configuration.
Prediction: Use the predict.py script to generate predictions on new data.
Model Evaluation
The model was evaluated using key metrics:

## Accuracy: 93%
F1 Score: 82%
Precision & Recall: Evaluated for balanced predictive performance

## Useful Resources
https://scikit-learn.org/: For reference on machine learning algorithms and evaluation metrics.
https://pandas.pydata.org/: For efficient data handling and preprocessing.
https://matplotlib.org/, https://seaborn.pydata.org/: For data visualization in exploratory data analysis.
https://www.ifrs.org/ (ECL) Overview by IFRS: Guidelines on ECL methodology and standards in credit risk assessment.
