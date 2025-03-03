# Predicting Birthweight with Machine Learning Models
**Author:** Emily Inga

## Project Overview
This project leverages machine learning techniques to predict the birth weight of newborns using a dataset containing maternal and neonatal health data. The dataset includes features such as gestation period, maternal age, height, weight, smoking status and parity, alongside the target variable - birthweight.

## The project is divided into the following key steps:
### 1. Data Preparation:
  - Loaded data directly from a public source
  - Performed exploratory data analysis (EDA) to uncover patterns and relationships
  - Cleaned and inputted missing values using median and mode
  - Visualized data through correlation matrices, pair plots, and histograms
### 2. Feature Selection:
  - Identified key features with the highest predictive power, such as gestation period, maternal weight, and smoking status
  - Excluded features like case ID and parity due to low predictive relevance
### 3. Model Development
  - Implemented two machine learning algorithms: Random Forest and k-Neares Neighbors (K-NN)
  - Partitioned data into training and testing sets, ensuring reproducibility and scaling for optimal model performance
### 4. Model Evaluation and Tuning
  - Evaluated model performance using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE)
  - Fine-tuned hyperparameters (e.g., n_estimators for Random Forest, k for K-NN) to improve model accuracy
### 5. Comparison and Insights:
  - Random Forest achieved an RMSE of 17.44, while K-NN with k = 11 achieved a lower RMSE of 16.94, making K-NN the more accurate model for this task
  - Smoking was negatively correlated with birth weight, while gestation was the most significant predictor

This project was created as a part of a data science course at Northeastern University
