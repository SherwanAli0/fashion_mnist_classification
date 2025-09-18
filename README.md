# fashion_mnist_classification
# Deep Learning with PyTorch

This project is part of the AI Engineering course module **"Deep Learning with PyTorch"**.

## Overview

This repository implements a convolutional neural network (CNN) using PyTorch to classify images from the Fashion MNIST dataset. The images are resized to 16x16 pixels before being processed by the network. The CNN model incorporates batch normalization to improve training stability and accuracy.

## Features

- Resizes Fashion MNIST images to 16x16 pixels  
- Applies data transformations including tensor conversion  
- CNN with two convolutional layers and batch normalization  
- Max pooling layers to reduce spatial dimensions  
- Trains using cross-entropy loss and SGD optimizer  
- Evaluates validation accuracy after each epoch  
- Visualizes sample images and training progress with matplotlib  

## Requirements

- Python 3.7 or later  
- PyTorch (torch)  
- torchvision  
- matplotlib  

All dependencies can be installed via:

pip install -r requirements.txt

## Usage

To run the training and evaluation, simply execute:

python fashion_mnist_cnn.py

The script will:

- Download the Fashion MNIST dataset if not already present  
- Resize and preprocess images  
- Train the CNN model for 5 epochs by default  
- Display a few sample images from the validation set  
- Show training loss and validation accuracy per epoch  
- Plot the training loss and accuracy curves after training  

## Project Structure

- `fashion_mnist_cnn.py`: Main Python script implementing data loading, model, training, and visualization  
- `requirements.txt`: Lists the Python dependencies needed    
- `README.md`: This file, project overview and usage instructions  

## Notes

This implementation is designed for educational purposes in the context of the AI Engineering course. It demonstrates key PyTorch concepts including dataset transforms, CNN construction, batch normalization, training loops, and performance plotting.

---

