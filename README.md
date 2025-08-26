**📝 Handwritten Digit Recognition using ANN (TensorFlow/Keras)**

**Introduction**

Handwritten digit recognition is a classic problem in the field of machine learning and computer vision.
In this project, I built an Artificial Neural Network (ANN) using TensorFlow/Keras to classify digits (0–9) from the MNIST dataset.
The MNIST dataset contains 70,000 grayscale images of handwritten digits (60,000 for training and 10,000 for testing), each of size 28×28 pixels.

This project demonstrates:

Data preprocessing (normalization & reshaping).

Building and training an ANN from scratch using Keras.

Model evaluation using accuracy, confusion matrix, and classification report.

Visualization of training history and predictions.

**📊 Dataset**

Source: MNIST (available directly in Keras).

Training samples: 60,000

Testing samples: 10,000

Image size: 28×28 pixels (grayscale)

**Model Architecture**

Input layer: 784 neurons (flattened 28×28 image)

Hidden layer 1: Dense (128 neurons, ReLU)

Hidden layer 2: Dense (64 neurons, ReLU)

Output layer: Dense (10 neurons, Softmax)

**Results**

Final Test Accuracy: ~98%

Confusion matrix & classification report included in the notebook.

**This project is a part of my Machine Learning portfolio.**