# Neural-Networks
Implementation of Non-Linear Regression and Non-Linear Logistic Regression using 5-fold Cross Validation to tune Neural Network Hyperparameters.

## Overview

Neural networks are computing systems inspired by the biological neural networks that constitute human brains. The neural network itself is not an algorithm, but rather a framework for many different machine learning algorithms to work together and process complex data inputs [source wiki]. Neural Network is a mathematical function that maps a given input to a desired output. A simple neural netwok consists of below components:

- An input layer, x
- An arbitrary amount of hidden layers
- An output layer, y
- A set of weights and biases between each layer, W and b
- A choice of activation function for each hidden layer, σ

Iterations in Training of Neural Networks consists of below steps:

#### Feed Forward: 
Fitting the data with Multi Layer Perceptron is a connective optimization problem with non-smooth step function. So, we use a smooth function which we call **activation function**. To evaluate the "goodness" of our predictions, we use **Loss Function**.

#### Loss Function:
Degree of how far we are off our predictions. The most common choice of Loss Function is **sum-of-sqaures error** as loss function. The sum-of-squares error is simply the square of sum of the difference between each predicted value and the actual value. 

#### Backpropogation:
Our goal in training is to find the best set of weights and bias to minimize the loss function. To find the appropriate weights and bias, we find the derivative of the loss function with respect to the weights and biases, called **Gradient Descent**

This is the basic overview of this repository. In this repository, I will implement Non-Linear Regression and Non-Linear Logistic Regression using the weights and bias updates which we will discuss in the coming sections of this notebook. I will also use 5-fold Cross Validation to find a good neural network parameters.
