# Predicting-Diabetes-Progression-Using-Artificial-Neural-Networks

## Overview
This Jupyter Notebook provides a comprehensive analysis for predicting diabetes progression using Artificial Neural Networks (ANN). The goal is to explore and model diabetes progression data to make accurate predictions.

## Project Details

- **Project Name**: Predicting Diabetes Progression Using Artificial Neural Networks
- **Platform**: Entry App
- **Start Date**: 14-08-2024
- **Project Lead**: Usha
- **Mentor**: Jisma TK
- **dataset**: Diabetes dataset available in the sklearn library.

  ## Introduction
This section introduces the problem of predicting diabetes progression and outlines the objectives of the project. It provides context and explains the significance of the analysis.

## Data Exploration

- **Libraries Used**: numpy, pandas, matplotlib, seaborn
- **Dataset Overview**: Loading and inspecting the dataset, including summary statistics and visualizations.
  ## Data Preprocessing

- **Handling Missing Values**: Methods for managing missing data.
- **Feature Scaling**: Techniques for normalizing and scaling features.
- **Encoding**: Transforming categorical variables into numerical format.
  ## Model Building

- **Artificial Neural Network (ANN)**: Building and training an ANN model.
- **Hyperparameter Tuning**: Optimizing model parameters for better performance.

## Evaluation

- **Performance Metrics**: Metrics used to evaluate model performance.
- **Results**: Summary of the ANN model’s performance on the test set.


## Conclusion and Findings

- **Model Performance:**
  - **Mean Squared Error (MSE):** The MSE of the model is approximately 2948.73. This indicates the average squared difference between predicted and actual values. While the MSE is not excessively high, suggesting moderate accuracy, there is room for improvement.
  - **R² Score:** The R² score is about 0.44. This means that the model explains approximately 44% of the variance in the target variable. An R² score of 0.44 reflects moderate performance, showing that the model accounts for a significant portion of the variability but could be improved further.

**Overall Assessment:**
The model shows moderate performance. Further refinement, such as tuning model parameters, experimenting with different architectures, or incorporating additional features, could enhance predictive accuracy.



