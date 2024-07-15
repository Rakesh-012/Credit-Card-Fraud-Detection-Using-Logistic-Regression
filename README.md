# Credit Card Fraud Detection using Logistic Regression
This repository contains code for detecting credit card fraud using Logistic Regression. The model is trained on a dataset of credit card transactions labeled as either normal or fraudulent.

## Dataset
The dataset used for training the model can be found on 
The dataset used for training the model can be found on [Kaggle.](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) You can also download the dataset from Google Drive.

The dataset contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred over two days, with 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, with the positive class (frauds) accounting for 0.172% of all transactions.

## Dependencies
The following dependencies are required to run the code in this repository:
- Python 3.x
- NumPy
- Pandas
- Scikit-learn (includes LogisticRegression)

## You can install the required dependencies using the following command:
``` pip install numpy pandas scikit-learn ```

## Code Overview
The code provided performs the following tasks:

** Data Loading and Basic Exploration: ** Loads the dataset and performs basic exploratory analysis such as checking shape, info, and the first few rows of the data.

** Data Cleaning: ** Removes duplicate rows and checks for missing values.

#### Data Preparation:
Balances the dataset by sampling normal transactions to match the number of fraudulent transactions for better model training.

#### Model Training:
Uses Logistic Regression to train a classification model on the balanced dataset.

#### Model Evaluation:
Calculates the accuracy scores on both training and testing data to evaluate model performance.

## Acknowledgments
The dataset used in this project was obtained from Kaggle.
