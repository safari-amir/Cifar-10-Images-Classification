# CIFAR-10 Classification with CNN

## Overview
This project implements a Convolutional Neural Network (CNN) for image classification on the CIFAR-10 dataset. The model is designed with fewer than 400,000 parameters while maintaining high accuracy. Various generalization techniques, such as dropout, batch normalization, weight decay, learning rate scheduling, and early stopping, are applied to enhance performance.

## Features
- **CNN-based Architecture**: Three convolutional blocks with increasing filter sizes (32, 64, 128).
- **Regularization Techniques**:
  - Dropout for reducing overfitting.
  - Batch Normalization for stabilizing training.
  - Weight Decay (L2 Regularization) to penalize large weights.
- **Learning Rate Scheduling**: Adjusts the learning rate dynamically for better convergence.
- **Early Stopping**: Stops training if validation loss does not improve for a specified number of epochs.
- **Data Augmentation**: Random transformations are applied to training images for better generalization.
- **Model Checkpointing**: The best model based on validation accuracy is saved.

## Dataset
- **Name**: CIFAR-10
- **Images**: 60,000 color images (32x32 pixels, 3 channels)
- **Classes**: 10 (airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck)
- **Training Set**: 50,000 images
- **Test Set**: 10,000 images

