# MNIST Multilayer Perceptron (MLP) Classification
This repository contains a machine learning model that focuses on classifying handwritten digits from the MNIST dataset into 10 different classes (0 to 9) using a multilayer perceptron (MLP) model. The MLP model is implemented entirely from scratch using NumPy, enabling us to understand the fundamental concepts of neural networks and their training process.

## Dataset
The project utilizes the MNIST dataset which consists of a large collection of grayscale images of handwritten digits. Each image is a 28x28 pixel array and the corresponding labels represent the digit in the image (ranging from 0 to 9).

## Multilayer Perceptron Model
The core of this project is the implementation of a multilayer perceptron model using NumPy. The model architecture consists of multiple layers:

**Input Layer**: The input layer corresponds to the flattened 28x28 image pixels. The number of neurons in this layer is determined by the total number of pixels in each image.

**Hidden Layers**: The MLP model includes one or more hidden layers. Each hidden layer is fully connected and employs the Rectified Linear Unit (ReLU) activation function for introducing non-linearity. The number of neurons in each hidden layer can be customized.

**Output Layer**: The output layer has 10 neurons, each representing one class (0 to 9). The Softmax activation function is applied to produce probability scores for each class.

## Contributions
Contributions to this project are encouraged. If you encounter any issues or have suggestions for improvements feel free to open an issue or submit a pull request.
