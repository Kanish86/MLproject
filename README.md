## TensorFlow MNIST Classifier

This script is a TensorFlow implementation of a neural network classifier for the MNIST handwritten digits dataset.

### Description

The script performs the following tasks:

1. Imports TensorFlow library and loads the MNIST dataset.
2. Defines the neural network architecture with input, hidden, and output layers.
3. Sets hyperparameters such as learning rate, number of iterations, batch size, and dropout rate.
4. Builds the computational graph for the neural network model.
5. Trains the model on mini-batches of the training dataset.
6. Prints the loss and accuracy per minibatch during training.
7. Evaluates the accuracy of the trained model on the test dataset.

### Prerequisites

Before running the script, ensure you have TensorFlow installed. You can install TensorFlow via pip:

```bash
pip install tensorflow
```

### Outputs

The script prints the loss and accuracy per minibatch during training and the final accuracy on the test dataset.

### Note

- The script utilizes TensorFlow's built-in functions for loading and preprocessing the MNIST dataset.
- Adjust hyperparameters and neural network architecture as needed for experimentation.
- Ensure you have sufficient computational resources to train the model, especially for a large number of iterations.
