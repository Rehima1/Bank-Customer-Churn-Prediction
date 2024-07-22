# Bank-Customer-Churn-Prediction
## Description

This project involves predicting customer churn in the banking industry using Random Forest Classifier, and XGBoost. Customer churn refers to the loss of clients or customers, which is crucial for banks to predict and mitigate in order to retain valuable clients. The project build a predictive models based on customer data.

## Features

- Data Preprocessing: Cleaning and preparing the dataset for analysis.
- Exploratory Data Analysis (EDA): Understanding data distribution and correlations.
- Model Building: Training and evaluating multiple models such as Random Forest, and XGBoost.
- Evaluation Metrics: Assessing model performance using accuracy, confusion matrix, and other metrics.
- Visualization: Generating visualizations for model evaluation .

## Data

The dataset contains customer information and their churn status. Features include demographics, account details, and transaction history. The data was sourced from [[[insert source](https://www.kaggle.com/datasets/shantanudhakadd/bank-customer-churn-prediction/data)] and is available in the `data/` directory.

## Results

### Model Performance

- **XGBoost Model**
  - **Train Accuracy**: 96.97%
  - **Validation Accuracy**: 84.65%
  - **Test Accuracy**: 86.15%

- **Random Forest Model**
  - **Train Accuracy**: 88.23%
  - **Validation Accuracy**: 86.15%
  - **Test Accuracy**: 86.10%

### Confusion Matrices

Confusion matrices for both the validation and test sets are provided in the `results` directory, along with feature importance plots.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Video Overview

Check out this video for an overview of the Bank Customer Churn Prediction project:

![Watch the video](media/overview.mp4)
