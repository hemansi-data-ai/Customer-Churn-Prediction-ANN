# Customer Churn Prediction using Artificial Neural Network (ANN)

## Project Overview

This project uses an Artificial Neural Network (ANN) to predict whether a telecom customer is likely to leave the company (Churn) or continue using its services.

The model is developed using Python, TensorFlow, and Keras.

## Problem Statement

Customer churn is an important business problem. Companies want to identify customers who may leave their services so they can take steps to improve customer retention.

The goal of this project is to build a Deep Learning model that predicts customer churn based on customer information and service usage.

## Dataset

**Dataset:** Telco Customer Churn

The dataset contains customer information, including:

- Gender
- Senior Citizen
- Partner and Dependents
- Tenure
- Phone and Internet Services
- Online Security and Tech Support
- Contract Type
- Payment Method
- Monthly Charges
- Total Charges

**Target Variable:** Churn

- 0 = No Churn
- 1 = Churn

## Technologies and Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- TensorFlow
- Keras

## Project Workflow

1. Data Loading and Exploration
2. Data Cleaning and Preprocessing
3. Handling Missing Values
4. Encoding Categorical Features using One-Hot Encoding
5. Feature Scaling using StandardScaler
6. Train-Test Split
7. Building an Artificial Neural Network
8. Model Training and Validation
9. Early Stopping and Dropout
10. Model Evaluation using Accuracy, Precision, Recall, F1-score, and Confusion Matrix
11. Training and Validation Curve Visualization

## ANN Architecture

- Input Layer
- Dense Layer (16 neurons, ReLU activation)
- Dropout Layer (30%)
- Dense Layer (8 neurons, ReLU activation)
- Dropout Layer (20%)
- Output Layer (1 neuron, Sigmoid activation)

**Optimizer:** SGD

**Loss Function:** Binary Cross-Entropy

## Model Performance

Test Accuracy: **81.26%**

## Key Learnings

- Understanding Artificial Neural Networks
- Building binary classification models using TensorFlow/Keras
- Data preprocessing for Deep Learning
- Understanding training and validation curves
- Identifying overfitting
- Applying Dropout and Early Stopping
- Evaluating classification models

## Future Improvements

- Experiment with different ANN architectures and hyperparameters.
- Improve churn-class recall.
- Experiment with classification thresholds.
- Compare ANN performance with traditional Machine Learning algorithms.

## Author

**Hemansi**  
Data Analytics & AI/ML Learner  
GitHub: https://github.com/hemansi-data-ai  
