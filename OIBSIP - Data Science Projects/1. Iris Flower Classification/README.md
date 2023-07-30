# Iris Flower Classification

This repository contains a machine learning project focused on classifying IRIS flowers into different species using Support Vector Machines (SVM), Logistic Regression (LR) and Decision Tree Classifier algorithms. The goal of this project is to train a machine learning model using the Machine learning algorithms that can learn from the petal and sepal measurements of the iris species and classify them .

## Project Overview

This project aims to demonstrate the practical application of machine learning in the field of botany and contribute to the understanding and conservation of iris flower species.

## Dataset

The project utilizes the well-known Iris dataset, which includes measurements of sepal length, sepal width, petal length, and petal width for three different iris species: Setosa, Versicolor, and Virginica. The dataset is commonly used as a benchmark for classification algorithms due to its simplicity and distinct species characteristics.

## Algorithms

The classification task is performed using these algorithms:

1. Support Vector Machines (SVM): SVM is a powerful algorithm for binary and multi-class classification. It constructs a hyperplane or set of hyperplanes to separate data points belonging to different classes, maximizing the margin between them.

2. Logistic Regression (LR): LR is a widely used algorithm for binary classification that can be extended to handle multi-class problems. It models the relationship between the features and the probabilities of the different classes using a logistic function.

3. Decision Tree: Decision Tree is a tree-based algorithm that recursively partitions the feature space based on the attribute values. It creates a set of rules to make predictions by traversing the tree from the root node to the leaf nodes.

## Usage & Implementation

To run the classification algorithms and evaluate their performance, follow the instructions below:

1. Install the required dependencies listed in the `requirements.txt` file.

2. Run the `iris_classification.py` script, which loads the dataset, preprocesses the data, trains the SVM, LR, and Decision Tree models, and evaluates their accuracy on a held-out test set.

3. Experiment with different hyperparameters, feature engineering techniques, or other modifications to improve the classification results.

### Technology Stack

### **Programming Language**:

**Python**: Python is a popular choice for machine learning projects due to its extensive libraries and frameworks for data manipulation, visualization, and modeling.

### **Data Manipulation and Analysis**:

**NumPy**: NumPy is used for numerical computing in Python and provides support for handling arrays and matrices, which are fundamental data structures for machine learning.

**Pandas**: Pandas is a powerful library for data manipulation and analysis, which is particularly useful for handling structured datasets.

**Machine Learning Libraries**:

**Scikit-learn**: Scikit-learn is a comprehensive machine learning library that offers various algorithms for classification, regression, clustering, and more. It also provides tools for model evaluation and selection.

### **Data Visualization**:

**Matplotlib**: Matplotlib is a widely used plotting library in Python for creating visualizations, such as line plots, scatter plots, histograms, etc.

**Seaborn**: Seaborn is a higher-level data visualization library that works well with Pandas DataFrames and provides attractive statistical graphics.

### **Development Environment**:

**Jupyter Notebook**: These interactive computing environments are often used for prototyping, experimentation, and data exploration, making it easier to share code and visualizations.

### **Version Control**:

**Git**: Git is a distributed version control system that helps manage changes to the project's codebase efficiently and enables collaboration among team members.

Feel free to explore the code, understand the implementation details, and adapt it for your own classification tasks.
