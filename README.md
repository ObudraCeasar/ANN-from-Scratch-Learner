# ANN-from-Scratch-Learner
Here are the ANN basics codes and notes.
Neural networks are powerful ML models used in image classification, speech recognition, and natural language processing etc.

On can use the many high-level libraries available to build and train neural networks easily, but 2it’s important to have a fundamental understanding of the underlying concepts and mathematics behind them.

So, here we build an ANN from scratch using only the numpy and math libraries in Python. The key concepts handled are forward and backward propagation, activation functions, and loss functions.Each of these steps will be implemented, including initialization, training, and prediction.

Building the neural network model involves the following:

1. Load and prepare the dataset.
2. Define the neural network architecture.
3. Initialize the weights and biases.
4. Define the activation function(s).
5. Implement the forward propagation algorithm.
6. Define the loss function.
7. Implement the backward propagation algorithm.
8. Train the neural network.
9. Evaluate the model performance on test data.
The details are as below:

Step 1: Load and prepare the dataset
- Load the dataset and prepare it for training. E.g a simple toy dataset with two features and two classes created using the below code:
- import numpy as np

np.random.seed(0)

# create a toy dataset
X = np.array([[0, 0], [0, 1], [1, 0], [1, 1]])
y = np.array([[0], [1], [1], [0]])
