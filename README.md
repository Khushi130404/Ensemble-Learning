# Ensemble_Learning

This project demonstrates various ensemble learning techniques using Jupyter Notebook. The goal is to explore how ensemble methods can improve the performance of machine learning models for both regression and classification tasks.

## Techniques Covered

The following ensemble methods have been implemented and evaluated in this project :
- Adaboost (Adaptive Boosting)
- Bagging (Bootstrap Aggregating)
- Gradient Boosting
- Random Forest
- Stacking Ensemble
- Voting Ensemble

## Problem Types

The project includes implementations for :

- Regression Problems

- Classification Problems

## Project Structure

The project is organized into the following sections :

### 1. Data Preprocessing
   
- Loading datasets
- Handling missing values

### 2. Feature scaling
   
- Model Implementation
- Implementing each ensemble technique for regression and classification tasks

### 3. Model Evaluation

- Comparing model performance using metrics such as:
  - For Regression: Mean Squared Error (MSE), R-Squared (R²)
  - For Classification: Accuracy, Precision, Recall, F1-Score

## Ensemble Methods Overview

### 1. Adaboost (Adaptive Boosting)

- Works by combining multiple weak classifiers to create a strong classifier.
- Adjusts the weights of incorrectly classified instances to focus on difficult cases.

### 2. Bagging (Bootstrap Aggregating)

- Reduces variance by training multiple models on different subsets of the dataset.
- Combines predictions through averaging (for regression) or majority voting (for classification).

### 3. Gradient Boosting

- Builds models sequentially, with each new model correcting the errors of the previous ones.
- Suitable for both regression and classification tasks.

### 4. Random Forest

- An extension of bagging that uses decision trees as base learners.
- Introduces randomness by selecting a random subset of features for each split.

### 5. Stacking Ensemble

- Combines multiple models (base learners) by training a meta-model to make final predictions.
- Allows using different types of models as base learners.

### 6. Voting Ensemble

- Combines predictions from multiple models by voting (for classification) or averaging (for regression).
- Can be hard voting (majority vote) or soft voting (weighted probabilities).




