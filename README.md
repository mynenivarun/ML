Parkinson's Disease Progression Prediction
Overview

This project implements linear regression models from scratch to predict the progression of Parkinson's disease based on various features extracted from voice measurements. The dataset used focuses on predicting the motor_UPDRS score, a measure of Parkinson's disease severity, through multiple linear regression techniques, including single-variable, multi-variable, and stepwise regression analyses.
Objectives

`Linear Regression with One Variable: Predict motor_UPDRS using the PPE feature.`

`Linear Regression with Two Variables: Extend the model to include the NHR feature and analyze the impact on performance.`

`Stepwise Linear Regression: Employ both forward and backward stepwise regression to identify the most predictive features out of a given set.`

`Regularization and Feature Scaling: Investigate the effects of regularization and feature scaling on the best-performing model.`

Setup and Running
Prerequisites

`Python 3.12`
`NumPy`
`pandas`
`Matplotlib`

Ensure you have the above prerequisites installed on your system. You can install them using pip:

bash

    pip install numpy pandas matplotlib

Dataset

The dataset is stored in data/parkinsons_data.csv. Ensure that this file is located in the data directory relative to the main script.
Running the Code

Navigate to the project directory and run the Python script using:

bash

    python main.py

Replace main.py with the name of your script. The script will:

`Load the dataset.`

`Perform linear regression analysis with varying numbers of input features.`

`Evaluate model performance using metrics such as Mean Squared Error (MSE), R-squared, and Adjusted R-squared.`

`Display graphs for visual analysis of the model performance.`

Analysis and Results

The results directory contains output graphs and a detailed analysis report in PDF format. This report discusses the methodology, performance evaluation, and insights gained from the linear regression models developed.
