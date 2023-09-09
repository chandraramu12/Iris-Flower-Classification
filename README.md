# Iris-Flower-Classification

This repository contains Python code for a basic iris flower classification task using the Iris dataset. The task involves predicting the species of iris flowers based on features like sepal length, sepal width, petal length, and petal width.

## Table of Contents
- [Introduction](#introduction)
- [Setup](#setup)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Model Training](#model-training)
- [Model Evaluation](#model-evaluation)
- [Testing](#testing)
- [Usage](#usage)


## Introduction
In this project, we use a Logistic Regression model to perform the classification. Logistic Regression is a simple and widely used machine learning algorithm for binary and multiclass classification problems. It is used to make a prediction about a categorical variable versus a continuous one.

## Setup
To run the code, you'll need the following libraries installed:
- NumPy
- Matplotlib
- Seaborn
- Pandas
- Scikit-Learn

You can install these libraries using the following command:
```
pip install numpy matplotlib seaborn pandas scikit-learn
```

## Dataset
The Iris dataset is a popular dataset for classification tasks. It consists of 150 samples of iris flowers, each belonging to one of three species: setosa, versicolour, and virginica. The dataset provides four features: sepal length, sepal width, petal length, and petal width.


## Data Preprocessing
- Loading the dataset
- Removing the 'Iris-' prefix from species names
- Checking for missing values

## Exploratory Data Analysis
- Visualizing relationships between pairs of variables using pair plots
- Showing the distribution of species using a pie chart

## Model Training
- Separating features and target variables
- Splitting the dataset into training and testing sets
- Training a Logistic Regression model

## Model Evaluation
- Making predictions on the test set
- Calculating accuracy and generating a confusion matrix

## Testing
- Testing the model on some random input vectors to predict the species

## Usage
You can clone this repository and run the provided Python script to perform iris flower classification. Feel free to modify the code or use it as a starting point for your own projects.

