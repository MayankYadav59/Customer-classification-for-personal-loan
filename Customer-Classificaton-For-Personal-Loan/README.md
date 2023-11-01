# Customer Classification for Personal Loan


## Data Description
The project utilizes a dataset comprising data on 5000 customers, encompassing demographic information (age, income, etc.), the customer's relationship with the bank (mortgage, securities account, etc.), and the customer response to the last personal loan campaign (Personal Loan). Among these 5000 customers, only 480 (9.6%) accepted the personal loan offered in the earlier campaign.

## Project Overview
This project revolves around a bank, Thera Bank, seeking ways to convert liability customers into personal loan customers while retaining them as depositors. The previous campaign for liability customers achieved a healthy conversion rate of over 9%, encouraging the retail marketing department to design more effective target marketing campaigns with minimal budget spending. The project includes data cleaning, exploratory data analysis (EDA), data preparation, model training, prediction, model evaluation, and the utilization of ensemble learning methods.

## Notebook Contents
This project notebook comprises the following sections:
- Data cleaning
- Exploratory data analysis (EDA)
- Data preparation for model training
- Training and prediction using various classification models
- Model evaluation
- Application of ensemble learning methods

## Objective
The primary objective is classification, specifically predicting the likelihood of a liability customer purchasing personal loans. To achieve this, a model is built to predict which customers are most likely to accept personal loan offers based on their relationship with the bank and various features in the dataset. The Supervised Learning methods, namely **Logistic Regression**, **Naive Bayes (NB)**, and **K-Nearest Neighbors (KNN)**, are used for model selection.

## Problem Statement and Metric
- The project addresses a classification problem.
- The target variable for classification is **Personal Loan**.
- The goal is to build a model that achieves optimal classification on the target variable.
- Given imbalanced data, the project focuses on the **Recall** score as the primary evaluation metric.

## Usage
To explore this project, follow these steps:
1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Review the Jupyter Notebook files for detailed code and analysis.
4. Experiment with different classification models and techniques.
5. Analyze the model evaluation results.

## Dependencies
Ensure you have the following libraries and tools installed to run the project successfully:
- Python 3.x
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Acknowledgments
This project offers an analysis of a bank's personal loan campaign. Feel free to use it as a reference or starting point for your own classification projects.

