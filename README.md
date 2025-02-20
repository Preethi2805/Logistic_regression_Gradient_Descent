# Logistic Regression with Gradient Descent

This repository implements a logistic regression model from scratch and applies gradient descent to optimize its parameters. The project consists of two main tasks:

1. **Task 1**: Implement logistic regression with a function to compute the gradient of the cross-entropy loss. 
2. **Task 2**: Train a logistic regression model on the heart disease dataset and visualize the training process.

## Task 1: Logistic Regression and Gradient Computation
In this task, the following functions are implemented:
- `predict_prob(w, x)`: Computes the predicted probability of the positive class for a given feature vector `x` and weight vector `w` using the logistic function.
- `compute_gradient(ys, xs, w)`: Computes the gradient of the cross-entropy loss with respect to the weight vector `w`, using the true labels `ys` and feature vectors `xs`.

To verify the gradient computation, the model is trained on a synthetic dataset, where the gradient at the true parameters should be close to zero.

## Task 2: Logistic Regression Model Training with Gradient Descent
In this task, the heart disease dataset (`heart.csv`) is used to train a logistic regression model using gradient descent. Key steps include:
- Data preprocessing: Categorical features ("cp" and "restecg") are one-hot encoded.
- Gradient descent optimization: The parameter vector is updated iteratively, and convergence is tracked based on the loss function.
- Training process: The model is trained for 10 epochs, with a learning rate of `1e-4` and a tolerance of `1e-6`. The loss is tracked and plotted over time.
