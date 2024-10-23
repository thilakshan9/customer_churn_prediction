# Customer Churning Predictor

## Introduction

**Customer Churning Predictor** is a tool that utilizes multiple machine learning models to predict customer churn. This project leverages classical machine learning techniques such as:

- XGBoost
- Decision Trees
- Random Forest
- K-Nearest Neighbours (KNN)

By averaging the predictions from these diverse models, this project delivers a more robust prediction of how likely a customer is to leave. Additionally, it provides AI-generated explanations and personalized email outreach based on the predictions.

## Features

- **Multiple Model Predictions**: Leverage different machine learning algorithms to provide reliable churn predictions.
- **Graphical Visualisations**: Display visual insights to better understand customer data and model predictions.
- **AI-Generated Explanation**: Using LLAMA 3.1, automatically generate detailed explanations for each prediction.
- **Personalised Email**: Create customized emails for customer outreach based on churn predictions.

## Data Requirements

To make a churn prediction, the following customer data fields are required:

- `CreditScore`
- `Geography`
- `Gender`
- `Age`
- `Tenure`
- `Balance`
- `NumOfProducts`
- `HasCrCard`
- `IsActiveMember`
- `EstimatedSalary`

## Workflow

The project follows these key steps:

1. **Data Preparation**: Downloaded, cleaned, and normalized the bank's customer dataset.
2. **Feature Engineering & Visualization**: Extracted meaningful insights and visualized patterns in the data to guide modeling decisions.
3. **Model Training & Tuning**: Trained multiple machine learning models, evaluated their accuracy, and refined them through hyperparameter tuning.
4. **Web Application Development**: Created a web app for real-time inference using trained models. Integrated LLAMA 3.1 for generating explanations and personalized emails for outreach.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
