# Convolutional-Neural-Network-with-MNIST-Hand-written-dataset

This project implements a Convolutional Neural Network (CNN) to classify hand-written digits from the MNIST dataset using PyTorch.

## Project Details
Dataset: MNIST (Modified National Institute of Standards and Technology) dataset is a collection of 60,000 training images and 10,000 testing images of handwritten digits, commonly used for training various image processing systems.

Model: The CNN model is designed with two convolutional layers followed by max-pooling layers, and fully connected layers for classification


## Dependencies

- torch
- torchvision
- matplotlib
- pandas
- Numpy

## Training 

The model was built using two convolutional layers of 12 and 24 filter kernels respectively and two max pooling. 20% dropped out to prevent overfittting before sending to a fully connected layer. Adam optimizer was used for back propagation using cross entropy loss as loss criteria.  Training over 10 epochs yielded an optimal result. Accuracy was used as evaluation metric and confusion matrix plotted for visualization


