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

## Training 

The model was initially trained for 11 epochs, but it was observed that the test loss started increasing after the 4th epoch. To mitigate overfitting, the model was retrained for 3 epochs, which resulted in improved performance.

## Contributing
If you'd like to contribute to this project, please follow these steps:

  1.Fork the repository.
  2. Create a new branch for your feature or bug fix.
  3. Make your changes and open a pull request.
  4. Your pull request will be reviewed, and once approved, it will be merged.

