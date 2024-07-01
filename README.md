# Digit Recognition Model

This repository contains a digit recognition model built using Python, TensorFlow

## Introduction
This project aims to develop a model that can accurately recognize handwritten digits. Handwritten digit recognition is a common task in the field of computer vision and has applications in various domains such as postal mail sorting, bank check processing, and more.

## Dataset
The model is trained on the MNIST dataset, which consists of 60,000 training images and 10,000 test images of handwritten digits (0-9). Each image is 28x28 pixels in grayscale.

## Model Architecture
Describe the architecture of your model here. For example:
- Input Layer: 28x28 grayscale images
- Convolutional Layers: [details of conv layers]
- Fully Connected Layers: [details of dense layers]
- Output Layer: 10 neurons with softmax activation (for 10 digit classes)

- ## Training
Explain the training process, including:
- Loss function: [e.g., Categorical Cross-Entropy]
- Optimizer: [e.g., Adam]
- Number of epochs: [e.g., 10, 20]
- Batch size: [e.g., 32, 64]
- Any data augmentation techniques used

## Evaluation
Describe how the model's performance is evaluated. Include metrics such as accuracy, precision, recall, F1-score, etc.
