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
* `iris.csv`: Dataset file
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

- Python 3.x
- Jupyter Notebook
- numpy
- pandas
- matplotlib
- sklearn

Install the dependencies using:
```bash
pip install numpy pandas matplotlib sklearn jupyter
```

## Usage

1. Clone the repository

```bash
git clone https://github.com/yourusername/k-nearest-multiclass.git
```

2. Navigate to the project directory

```bash
cd k-nearest-multiclass
```

3. Open the Jupyter Notebook

```bash
jupyter notebook kNN_multiclass.ipynb
```

4. Run the cells in the notebook to see the implementation and results. 

## Resources

- **Dr. Hyuk Cho**: Provided guidance, resources, and code snippets for the project.
- [k-Nearest Neighbors Algorithm in Python and scikit-learn](https://realpython.com/knn-python/)
- [k-Nearest Neighbors From Scratch in Python](https://machinelearningmastery.com/tutorial-to-implement-k-nearest-neighbors-in-python-from-scratch/)
- [Introduction to k-Nearest Neighbors: A powerful Maching Learning Algorithm](https://towardsdatascience.com/introduction-to-k-nearest-neighbors-3b534bb11d26)


## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.
