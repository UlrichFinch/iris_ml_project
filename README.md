# iris_ml_project
A simple machine learning project i made as a freshman in Data Science

## Introduction

This project explores the classic Iris flower dataset to classify iris flowers into one of three species (`Iris-setosa`, `Iris-versicolor`, `Iris-virginica`) based on their sepal and petal measurements. The primary goal is to build and evaluate a simple machine learning model (Decision Tree Classifier) for this multi-class classification task.

This notebook demonstrates key steps in a typical data science workflow, including:
* Loading and inspecting data.
* Exploratory Data Analysis (EDA) through visualization.
* Feature selection based on EDA insights.
* Model training using Scikit-learn.
* Model evaluation using simple train-test split and more robust cross-validation techniques.
* Comparing model performance with different feature sets.

## Dataset

The dataset used is the famous Iris dataset (`Iris.csv`), which contains 150 samples from three species of Iris flowers. There are four features (measured in centimeters):

* `SepalLengthCm`
* `SepalWidthCm`
* `PetalLengthCm`
* `PetalWidthCm`

The target variable is `Species`, which includes:

* `Iris-setosa`
* `Iris-versicolor`
* `Iris-virginica`

The dataset was found to have no missing values. The `Id` column was dropped as it's just an identifier.

## Requirements

This project uses standard Python data science libraries. You can install them using pip or conda.

* pandas
* numpy
* seaborn
* matplotlib
* scikit-learn

```bash
pip install pandas numpy seaborn matplotlib scikit-learn
