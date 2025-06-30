# OIBSIP Project 1 – Iris Flower Classification

This repository contains my submission for Project 1 of the Oasis Infobyte Data Science Internship.

## Task Objective

To classify iris flowers into species (Setosa, Versicolor, Virginica) based on features like sepal length, sepal width, petal length, and petal width using machine learning.

## Tools and Libraries Used

- Python
- Pandas
- scikit-learn

## Project Workflow

- Imported the dataset using Pandas
- Performed exploratory data analysis:
  - Viewed top records
  - Checked for null values
  - Dropped the `Id` column
- Encoded the target variable (`Species`) using LabelEncoder
- Split the data into training and testing sets using `train_test_split`
- Trained a K-Nearest Neighbors (KNN) classifier
- Evaluated the model using:
  - Accuracy score
  - Classification report
- Predicted the species for a new data point

## Model Performance

- Achieved **100% accuracy** on the test set with KNN classifier

## Learning Outcome

Learned how to preprocess data, encode categorical variables, split data, train a machine learning model, and evaluate its performance in Python.

## Status

Task Completed

## Author

Saranya Srinivas
