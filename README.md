# MNIST Image Classification with Neural Network
This project demonstrates building and training a neural network to classify images from the MNIST dataset using TensorFlow and Keras.

## Dataset
The MNIST dataset consists of 70,000 grayscale images of handwritten digits (0-9). It is divided into:

Training set: 60,000 images
Test set: 10,000 images
## Model Architecture
Input Layer: Flatten 28x28 images into a 1D array of 784 elements
Hidden Layer: Dense layer with 128 neurons and ReLU activation
Dropout Layer: Dropout rate of 0.2
Output Layer: Dense layer with 10 neurons (one for each digit)
## Training
The model is trained using the Adam optimizer and sparse categorical crossentropy loss function for 5 epochs.

### Evaluation
The model's accuracy is evaluated on the test set.
