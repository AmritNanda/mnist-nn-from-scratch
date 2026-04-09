# Simple MNIST Neural Network from Scratch

This repository contains a Jupyter Notebook (`Mnist-hardcoded.ipynb`) that implements a simple 2-layer Neural Network from scratch in Python to classify handwritten digits from the MNIST dataset. It uses only NumPy and Pandas, without relying on deep learning frameworks like TensorFlow or PyTorch.

## Overview
This project is inspired by Samson Zhang. I got the inspiration to make my own Neural Network.
This taught me the very basics of how a neural network works behind the scenes and gave me a different outlook
It includes the entire process from data loading to neural network training and validation:
- **Data Initialization & Preprocessing**: Loads the MNIST dataset and splits it into training and development sets.
- **Forward Propagation**: Implements mathematical operations for the weights and biases using ReLU and Softmax activations.
- **Backward Propagation**: Calculates gradients using derivative of the activation functions.
- **Gradient Descent**: Updates parameters using the computed gradients through multiple epochs.
- **Predictions & Evaluation**: Validates the model on test data to calculate its accuracy.

## Requirements
- Python 3
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

## Usage
1. Make sure you have the MNIST train dataset available as `mnist_number_train.csv` in the same directory as the notebook.
2. Launch Jupyter Notebook and open `Mnist-hardcoded.ipynb`.
3. Run the cells sequentially to observe the training process, predictions, and final accuracy.
