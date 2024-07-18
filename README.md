# MNIST Digit Recognition Neural Network

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Project Overview

This project implements a neural network from scratch to recognize handwritten digits using the MNIST dataset. The neural network is built without relying on high-level machine learning libraries, providing a deep understanding of the underlying algorithms and architectures.

## Features

- Custom implementation of a neural network
- Utilizes the MNIST dataset for handwritten digit recognition
- Implements various components including:
  - Dense (fully connected) layers
  - ReLU activation function
  - Softmax activation for output layer
  - Categorical Cross-Entropy loss
  - Adam optimizer
  - Dropout for regularization
- L1 and L2 regularization
- Learning rate decay
- Batch training
- Data normalization and one-hot encoding
- Train-test split for evaluation

## Dependencies

- numpy
- pandas
- matplotlib
- collections (Counter)
- time

## Neural Network Architecture

The neural network consists of the following layers:

1. Input layer: 784 neurons (28x28 pixel images)
2. Hidden layer 1: 128 neurons with ReLU activation and dropout
3. Hidden layer 2: 64 neurons with ReLU activation and dropout
4. Hidden layer 3: 32 neurons with ReLU activation
5. Output layer: 10 neurons (one for each digit) with Softmax activation

## License

This project is licensed under the MIT License - see the [LICENSE](https://opensource.org/licenses/MIT) file for details.

## Author

Keanu Donovan

## Acknowledgments

- The MNIST dataset providers
