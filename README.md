# Iris Flower Species Classification
This repository contains a Machine Learning project focused on classifying iris flower species using various classification algorithms. The project employs the popular scikit-learn library and explores Logistic Regression, K-Nearest Neighbors (KNN), Support Vector Machine (SVM), Decision Tree, Random Forest, and Naive Bayes algorithms to create predictive models for classifying iris flowers into three different species: Setosa, Versicolour, and Virginica.

## Problem Description
The main objective of this project is to build a machine learning model that can accurately classify iris flowers into one of the three species based on four features: sepal length, sepal width, petal length, and petal width.

## Dataset
The Iris Flower dataset consists of 150 samples, each with four features: sepal length, sepal width, petal length, and petal width. These samples are labeled with the corresponding species they belong to: Setosa, Versicolour, or Virginica.

## Implementation
The project involves the following steps:

1. Data Preprocessing: The dataset is loaded and preprocessed to handle any missing values or anomalies.

2. Data Splitting: The dataset is divided into a training set and a test set. The training set is used to train the logistic regression model, while the test set is used to evaluate the model's performance.

3. Model Training: A logistic regression model is trained using the features from the training dataset and their corresponding labels.

4. Model Evaluation: The accuracy of the trained model is calculated using the test dataset. This accuracy gives an indication of how well the model can classify new, unseen samples.

5. Prediction: The trained model is used to predict the species of iris flowers in the test dataset.
