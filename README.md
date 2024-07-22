# Bank-Customer-Churn-Prediction
## Description

This project involves predicting customer churn in the banking industry using Random Forest Classifier, and XGBoost. Customer churn refers to the loss of clients or customers, which is crucial for banks to predict and mitigate in order to retain valuable clients. The project build a predictive models based on customer data.

Entire code can be found [here](https://github.com/Rehima1/Bank-Customer-Churn-Prediction/blob/main/Bank_Customer_Churn_Prediction.ipynb)

## Features

### Data Preprocessing: Cleaning and preparing the dataset for analysis.
  <img width="623" alt="image" src="https://github.com/user-attachments/assets/add890f9-a37e-4fd1-a9ac-4520a490cfdc">
  
### Exploratory Data Analysis (EDA): Understanding data distribution and correlations.
  ![image](https://github.com/user-attachments/assets/7fabb226-da16-4422-a4d1-94110a546702)
  ![image](https://github.com/user-attachments/assets/86e04285-2630-4e74-9a52-7f6aa327d55d)

### Model Building: Training and evaluating multiple models such as Random Forest, and XGBoost.
### Evaluation Metrics: Assessing model performance using accuracy, confusion matrix, and other metrics.
### Visualization: Generating visualizations for model evaluation .

## Data

The dataset contains customer information and their churn status. Features include demographics, account details, and transaction history. The data was sourced from [[[Data source](https://www.kaggle.com/datasets/shantanudhakadd/bank-customer-churn-prediction/data)].
<img width="908" alt="image" src="https://github.com/user-attachments/assets/6613be8e-fcd4-4fe5-a3e8-396b3aac1d00">

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

- **XGBoost Confusion Matrix**: ![image](https://github.com/user-attachments/assets/892d1a9a-4640-4440-9663-609b262c0185)
![image](https://github.com/user-attachments/assets/da166b95-b7bf-4061-a847-f100e7940dbe)

- **Random Forest Confusion Matrix**: ![image](https://github.com/user-attachments/assets/0252d5c3-5274-4f5e-8100-6fee56432f0d)
![image](https://github.com/user-attachments/assets/a8af1f66-a21c-4260-b63f-57d0f9c1ec63)


### Feature Importance

- **XGBoost Feature Importance**: ![image](https://github.com/user-attachments/assets/53fb7b7e-1b86-4c4c-bd37-e02a5054cb1a)

- **Random Forest Feature Importance**: ![image](https://github.com/user-attachments/assets/c3b1aed0-8507-464a-9279-ffc9fd7a8236)


## Video Overview

Check out this video for an overview of the Bank Customer Churn Prediction project:

![Watch the video](media/overview.mp4)

## Conclusion
The Bank Customer Churn Prediction project successfully developed two machine learning models, XGBoost and Random Forest, to predict customer churn. The XGBoost model achieved high training accuracy (96.97%) but showed signs of overfitting with lower validation accuracy (84.65%). In contrast, the Random Forest model demonstrated consistent performance across training (88.23%), validation (86.15%), and test sets (86.10%), indicating better generalization. Both models identified key features influencing churn, aiding in targeted customer retention strategies. While XGBoost captures complex patterns, Random Forest offers robust, interpretable results, making it a reliable choice for churn prediction.

