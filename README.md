# Industrial-Copper-Modeling

This project focuses on applying machine learning techniques to address challenges in the copper industry, including predicting selling prices and classifying leads based on their likelihood to convert into customers. The project utilizes advanced regression and classification models to provide valuable insights for stakeholders in the industry.

## Table of Contents
1. Introduction
2. Project Overview
3. Data
4. Methodology
5. Results
6. Usage
7. Dependencies

## Introduction
The copper industry faces challenges such as variability in pricing and lead conversion rates. Traditional methods for predicting selling prices and evaluating leads can be time-consuming and inefficient. This project aims to leverage machine learning techniques to build regression and classification models that can accurately predict selling prices and classify leads, respectively.

## Project Overview
- **Regression Model:** A Random Forest Regression model is trained to predict selling prices based on various features such as country, item type, application, and dimensions.
- **Classification Model:** A Random Forest Classifier is utilized to classify leads into two categories: Won (successful conversion) or Lost (unsuccessful conversion).
- **Streamlit Application:** A user-friendly web application is developed using Streamlit, allowing stakeholders to interact with the trained models and receive real-time predictions.

## Data
The dataset used in this project contains information on copper transactions, including features such as country, item type, quantity, customer details, and selling prices. Data preprocessing techniques are applied to handle missing values, outliers, and skewed distributions.

## Methodology
1. **Data Understanding**: Exploratory Data Analysis (EDA) is performed to understand the dataset's characteristics and distributions of features.
2. **Data Preprocessing:** Missing values are handled, outliers are detected and treated, and skewed features are transformed using appropriate techniques.
3. **Model Building:** Random Forest Regression and Random Forest Classification models are trained using the processed data.
4. **Evaluation:** Model performance is evaluated using appropriate metrics such as mean squared error (MSE), accuracy, precision, recall, and F1 score.
5. **Deployment:** A Streamlit web application is developed to deploy the trained models for real-time predictions.

## Results
- The regression model accurately predicts selling prices, with satisfactory performance metrics such as MSE and R-squared.
- The classification model demonstrates robust performance in classifying leads into Won or Lost categories, achieving high accuracy, precision, recall, and F1 score.
- Insights gained from the models provide valuable information for decision-making in the copper industry.

## Usage

To use the Streamlit application:

1. Install the required dependencies listed in the requirements.txt file.
2. Run the Streamlit app using the command streamlit run app.py.
3. Interact with the web application by entering input values and receiving predictions for selling prices or lead status.

## Dependencies
- Python 3.x
- Streamlit
- Scikit-learn
- Pandas
- NumPy
