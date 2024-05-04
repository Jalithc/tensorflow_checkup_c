# MNIST Handwritten Digit Recognition with TensorFlow/Keras

This repository contains a simple neural network implemented using TensorFlow/Keras to classify handwritten digits from the MNIST dataset.

## Overview

The MNIST dataset is a collection of 28x28 pixel grayscale images of handwritten digits (0 through 9). The goal of this project is to train a neural network model to accurately classify these digits.

## Model Architecture

The neural network model architecture is as follows:

1. **Input Layer**: Flatten layer to convert the 2D array of the image into a 1D array.
2. **Hidden Layer**: Dense layer with 128 neurons and ReLU activation function.
3. **Dropout Layer**: Dropout layer with a dropout rate of 0.2 to prevent overfitting.
4. **Output Layer**: Dense layer with 10 neurons (for 10 classes) and softmax activation function for multiclass classification.

## Training and Evaluation

The model is trained using the Adam optimizer and sparse categorical crossentropy loss function. After training, the model is evaluated on the test dataset to measure its performance in terms of accuracy.
