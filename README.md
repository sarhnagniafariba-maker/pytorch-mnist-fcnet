# MNIST Digit Classification with MLP and CNN

This project explores the classification of handwritten digits from the well-known MNIST dataset using two different neural network architectures built with PyTorch: a simple Multi-Layer Perceptron (MLP) and a Convolutional Neural Network (CNN).

The goal is to provide a clear, side-by-side comparison of these two approaches, demonstrating a complete workflow from data preparation to model evaluation.

## Key Features

*   **Data Handling:** Loads the MNIST dataset and applies necessary preprocessing steps, including conversion to tensors and normalization.
*   **Two Architectures:**
    *   **Multi-Layer Perceptron (MLP):** A fundamental, fully-connected neural network.
    *   **Convolutional Neural Network (CNN):** A more advanced architecture specifically designed for image recognition tasks.
*   **Training Pipeline:** Implements a standard training loop using the Adam optimizer and Cross-Entropy loss function to train both models.
*   **Performance Visualization:** Generates a plot of the training loss over iterations to visualize the learning progress of the models.
*   **Accuracy Evaluation:** Assesses the performance of the trained models on the unseen test dataset and reports the final classification accuracy.
