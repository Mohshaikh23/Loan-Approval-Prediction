# Loan Approval Prediction and Analysis

This repository contains code and analysis for predicting loan approval using machine learning. The project includes data preprocessing, exploration, feature engineering, visualization, and training a Support Vector Classifier (SVC) model for loan approval prediction.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Preparation and Model Training](#data-preparation-and-model-training)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The goal of this project is to predict loan approval status using various features such as applicant income, co-applicant income, loan amount, credit history, and more. A machine learning model is trained to predict whether a loan application will be approved or not.

## Prerequisites

### clone the repository : 

```bash
git clone https://github.com/Mohshaikh23/Loan-Approval-Prediction.git
```

Before running the code, ensure you have the required libraries installed:

- pandas
- numpy
- plotly
- scikit-learn

You can install them using the following command:

```bash
pip install pandas numpy plotly scikit-learn
```

## Data Preprocessing

The code starts with loading the loan dataset and dropping irrelevant columns. Missing values are handled by filling them with appropriate values based on the column type.

## Exploratory Data Analysis

The code explores the dataset using visualizations to understand the distribution of loan approval status, gender, marital status, education, income, loan amount, credit history, and more.

## Data Preparation and Model Training

The code converts categorical columns into numerical ones using one-hot encoding, splits the data into training and test sets, scales the numerical features using StandardScaler, and trains a Support Vector Classifier (SVC) model for loan approval prediction.

## Results

The trained model's predictions on the test set are displayed. The predicted loan approval values are added to the testing set and presented alongside the original features.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
