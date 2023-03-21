# SimpleLogistciRegression
# Logistic Regression Model for Iris Flower Data
This repository contains a Jupyter notebook that demonstrates a logistic regression model for the Iris Flower Data.

# Dataset
The Iris Flower Data is a famous multivariate dataset introduced by Ronald Fisher in 1936. The dataset consists of 150 samples of iris flowers, with each sample containing the following features:

Sepal Length (in cm)

Sepal Width (in cm)

Petal Length (in cm)

Petal Width (in cm)

Each sample is labeled with the species of the iris flower it represents:

Setosa

Versicolor

Virginica

The dataset is loaded using the scikit-learn load_iris() function and converted into a Pandas DataFrame.

# Model Training
The logistic regression model is trained using the training subset of the Iris Flower Data. The dependent variable (y) is the iris species, and the independent variables (X) are the four features of the iris flowers.

The model is trained using scikit-learn's LogisticRegression class with a maximum of 1000 iterations.

# Model Evaluation
The accuracy of the trained model is evaluated using the test subset of the Iris Flower Data. The accuracy is calculated using the score() method of the trained model.

# Manual Prediction
The trained model is used to manually predict the species of an iris flower based on its four features. A new data point with four feature values is passed to the model using the predict() method, and the predicted iris species is printed to the console.
