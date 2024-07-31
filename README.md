# Multi-Class Classification Using kNN  Model

A k-nearest neighbors (kNN) mdeol implemented to classify diffferent species of Iris flowers based on their features.

## Overview

This project This project demonstrates the implementation of a k-nearest neighbors (kNN) model to classify Iris flowers into three species: setosa, versicolor, and virginica. The dataset used is the famous Iris dataset. The kNN algorithm is implemented from scratch and also using the `sklearn` library for comparison. The project involves data preprocessing, model training, evaluation, and visualization.

## Table of Contents

- [Project Structure](#project-structure)
- [Dataset](#dataset)
- [Implementation](#implementation)
  - [From Scratch](#from-scratch)
  - [Using sklearn](#using-sklearn)
- [Results](#results)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Resources](#resources)
- [Contributing](#contributing)

## Project Structure

* `kNN_multiclass.ipynb`: Jupyter Notebook containing the implementation of the multi-class kNN model from scratch and using `sklearn`
* `iris.csv`: Dataset File
* `README.md`: Project Documentation 

## Dataset

The dataset used is `iris.csv`, which contains features of Iris flowers. The columns in the dataset are:
- `sepal_length`
- `sepal_width`
- `petal_length`
- `petal_width`
- `species` (class label): setosa, versicolor, or virginica

## Implementation

### From Scratch

The k-nearest neighbors (k-NN) model is first implemented from scratch using Python. The process involves:
1. Calculating the Euclidean distance between the test data point and all training data points.
2. Sorting the distances and selecting the k-nearest neighbors.
3. Performing majority voting to classify the test data point into one of the three species.

### Using sklearn

The `sklearn` library is then utilized to perform k-nearest neighbors classification on the same dataset. The steps include:
1. Importing the `KNeighborsClassifier` model from `sklearn`.
2. Fitting the model to the training dataset.
3. Making predictions and comparing them with the from-scratch implementation.

## Results

The results section compares the predictions made by the from-scratch implementation and the `sklearn` model, highlighting any differences and similarities. It includes performance metrics such as accuracy, precision, recall, and F1-score.

## Dependencies

## Usage

## Resources

## Contributing