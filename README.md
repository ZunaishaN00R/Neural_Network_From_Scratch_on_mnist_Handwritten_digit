# Neural Network on Plain Python for MNIST Dataset
Neural Network From Scratch on Mnist Handwritten Digit 

## Description

This project implements a simple neural network for classifying the MNIST dataset using plain Python without any deep learning frameworks. The dataset is loaded using Pandas, and the neural network is trained using a custom implementation of a logistic regression model. The model uses a sigmoid activation function and is trained using gradient descent.

The training process involves updating the weights and biases iteratively to minimize the logistic loss. The accuracy and loss are printed during training, and the training loss is plotted over epochs to visualize the learning process. The training stops either after reaching a specified number of epochs or when the loss falls below a certain threshold.

The trained model is then evaluated on the test set, and the accuracy is calculated and printed.

## Dataset

The MNIST dataset is used for training and testing the neural network. It is loaded using Pandas, with separate files for training and testing. The dataset consists of grayscale images of handwritten digits (0-9) with corresponding labels.

## Differences Between Neural Network Implementations

### Framework Usage

#### Keras/TensorFlow Model:

- Utilizes the high-level deep learning framework Keras with the TensorFlow backend.
- Abstraction allows for a concise and modular model definition.
- Training and evaluation are handled efficiently by the framework.

#### Plain Python Neural Network:

- Implements a neural network from scratch using basic Python, NumPy, and Pandas.
- Requires manual definition and adjustment of model parameters, such as weights and biases.
- Training loop and backpropagation are implemented manually.

### Model Complexity

#### Keras/TensorFlow Model:

- Uses a single dense layer with a sigmoid activation function for simplicity.
- Model definition is concise and abstracted.

#### Plain Python Neural Network:

- Implements logistic regression with a sigmoid activation function.
- Manual adjustment of weights and biases during training.

### Ease of Use

#### Keras/TensorFlow Model:

- Offers high-level abstractions, making it user-friendly.
- Training and evaluation are straightforward with built-in functions.

#### Plain Python Neural Network:

- Requires a deeper understanding of neural network concepts.
- Manual implementation of training loop and gradient descent.

### Performance

#### Keras/TensorFlow Model:

- Optimized and efficient implementation, suitable for large datasets.
- Takes advantage of hardware acceleration and parallel processing.

#### Plain Python Neural Network:

- Slower training process compared to optimized frameworks.
- Suitable for educational purposes and small datasets.

In summary, the Keras/TensorFlow model provides a more user-friendly and efficient approach to neural network implementation, while the plain Python neural network serves as an educational example for understanding the fundamentals of training a neural network from scratch. The choice between them depends on the user's objectives, experience level, and the scale of the project.
