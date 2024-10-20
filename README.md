MNIST Handwritten Digit Recognition with TensorFlow

This repository contains a notebook that demonstrates how to build and train a neural network model using TensorFlow and Keras to recognize handwritten digits from the MNIST dataset.

Overview

The notebook walks through the following steps:
1. Loading and normalizing the MNIST dataset : Preprocessing the data by scaling the pixel values between 0 and 1.
2. Model construction : Building a neural network with two hidden layers (256 and 128 neurons) and an output layer for classifying the 10 digits.
3. Training the model : Using the Adam optimizer and sparse categorical cross-entropy loss function to train the model on 10,000 samples.
4. Evaluating the model : Testing the model on unseen data and displaying accuracy and loss trends over training epochs.
5. Performance analysis : Visualizing correctly and incorrectly classified digits and summarizing the model's performance.


Requirements

- TensorFlow
- NumPy
- Matplotlib
"# Handwritten_Digit_Recognition_TensorFlow" 
