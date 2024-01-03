# Car Price Prediction

Predicting car prices based on various features using machine learning.

## Overview

This project aims to predict car prices by leveraging machine learning techniques. The dataset used for training and testing the model includes various features such as car specifications, mileage, engine power, and more.

## Table of Contents

- [Dataset](#dataset)
- [Features](#features)
- [Models](#models)
- [Evaluation](#evaluation)
- 
## Dataset

The dataset used for this project is sourced from Kaggle(data science community).
## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/car-price-prediction.git
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```


## Features

## Features

The dataset includes the following features:

1. **Make**: The brand or manufacturer of the car (categorical).

2. **Model**: The model name of the car (categorical).

3. **Year**: The manufacturing year of the car (numeric).

4. **Engine Fuel Type**: The type of fuel the car's engine uses (categorical).

5. **Engine HP**: The horsepower of the car's engine (numeric).

6. **Engine Cylinders**: The number of cylinders in the car's engine (numeric).

7. **Transmission Type**: The type of transmission in the car (categorical).

8. **Driven_Wheels**: The type of wheels the car is driven by (categorical).

9. **Number of Doors**: The number of doors on the car (numeric).

10. **Market Category**: The market category to which the car belongs (categorical).

11. **Vehicle Size**: The size category of the vehicle (categorical).

12. **Vehicle Style**: The style or body type of the vehicle (categorical).

13. **Highway MPG**: The miles per gallon on the highway (numeric).

14. **City MPG**: The miles per gallon in the city (numeric).

15. **Popularity**: The popularity score of the car (numeric).

16. **MSRP**: The Manufacturer's Suggested Retail Price (numeric).

Feel free to explore and use these features for building and improving your car price prediction model.


## Models

The project utilizes machine learning models for predicting car prices. The following models are implemented:

## Models

The following regression models, each fine-tuned with hyperparameter tuning using GridSearchCV, are implemented in this car price prediction project:

1. **Linear Regression**
   - Algorithm: Linear regression
   - Description: A basic linear regression model for predicting car prices.
   - Hyperparameter Tuning: Not applicable.

2. **Decision Tree Regression**
   - Algorithm: Decision tree regression
   - Description: A decision tree-based model for predicting car prices.
   - Hyperparameter Tuning: Fine-tuned using GridSearchCV for optimal parameters.

3. **Random Forest Regressor**
   - Algorithm: Random forest regression
   - Description: An ensemble model using a collection of decision trees for predicting car prices.
   - Hyperparameter Tuning: Fine-tuned using GridSearchCV for optimal parameters.

4. **XGBoost Regressor**
   - Algorithm: XGBoost regression
   - Description: An optimized gradient boosting model for predicting car prices.
   - Hyperparameter Tuning: Fine-tuned using GridSearchCV for optimal parameters.

5. **AdaBoost Regressor**
   - Algorithm: AdaBoost regression
   - Description: An ensemble model that combines weak learners for predicting car prices.
   - Hyperparameter Tuning: Fine-tuned using GridSearchCV for optimal parameters.

6. **Voting Ensemble with 5 Regressors**
   - Algorithm: Voting ensemble of various regressors
   - Description: An ensemble model combining predictions from multiple regression models.
   - Hyperparameter Tuning: Not applicable.

7. **Bagging Regressor**
   - Algorithm: Bagging regression
   - Description: An ensemble model that averages predictions from multiple models for predicting car prices.
   - Hyperparameter Tuning: Fine-tuned using GridSearchCV for optimal parameters.

For detailed information on hyperparameters and their optimal values, please refer to the corresponding model's documentation and implementation in the source code.


## Evaluation
All models Gives Accuracy of above 95 percent. Best Accuracy Achieved from XGB regressor i.e 98.5 percent and Adaboost regressor
The models are evaluated based on various metrics such as mean squared error, R-squared, mean absoulute error and Adjusted r-squared. The evaluation results can be found in the car-price-prediction.ipynb


