# Customer-Churn-Prediction-ML-Model
This repository contains a machine learning model for predicting customer churn using a Random Forest Classifier. Customer churn, also known as customer attrition, is a critical business challenge in various industries, including banking and telecommunications. This model aims to predict which customers are likely to leave a service or product.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Usage](#usage)
- [Data Preprocessing](#data-preprocessing)
- [Handling Imbalanced Data](#handling-imbalanced-data)
- [Model Training](#model-training)
- [Model Evaluation](#model-evaluation)
- [Results](#results)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Customer churn can result in significant revenue loss for businesses. This machine learning model uses a Random Forest Classifier to predict customer churn based on various features, helping businesses take proactive measures to retain customers.

## Dataset

The customer churn dataset used for this model is provided in the 'Churn_Modelling.csv' file. It contains customer information and churn labels. The dataset is preprocessed to handle missing values and label encoding.

## Usage

To use this customer churn prediction model:

1. Clone this repository to your local machine.
2. Ensure you have the required Python libraries installed (see Dependencies section).
3. Run the provided Python script, which includes data preprocessing, handling imbalanced data, model training, and evaluation.
4. View the model's performance metrics, including precision, recall, F1-score, ROC AUC, and accuracy.

Customize the model by adjusting hyperparameters or experimenting with different machine learning algorithms for optimal churn prediction.

## Data Preprocessing

Data preprocessing involves handling missing values and label encoding to convert categorical variables into numerical format.

## Handling Imbalanced Data

Imbalanced data is addressed using the Synthetic Minority Over-sampling Technique (SMOTE) to balance the dataset. SMOTE generates synthetic samples of the minority class to achieve a more balanced class distribution.

## Model Training

The machine learning model used in this project is a Random Forest Classifier. The model is trained on the preprocessed and balanced data to learn patterns and predict customer churn.

## Model Evaluation

The model's performance is evaluated using precision, recall, F1-score, ROC AUC, and accuracy. These metrics help assess how well the model can predict customer churn and its overall effectiveness.

## Results

The model's performance metrics are provided in the README or as part of the repository documentation. Users can analyze these results to determine the model's ability to predict customer churn.

## Dependencies

To run this project, you need the following dependencies:

- Python (3.x)
- NumPy
- Pandas
- Scikit-learn
- imbalanced-learn (SMOTE)

You can install these dependencies using `pip` or `conda`.

## Contributing

Contributions to this project are welcome! If you have ideas for improving the model, adding new features, or enhancing the documentation, please open an issue or submit a pull request.
