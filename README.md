# CNN Image Classification with PyTorch

This repository contains my deep learning project for multi-class image classification using a Convolutional Neural Network (CNN) built in PyTorch.

The project is implemented in a Jupyter Notebook (`.ipynb`) file and focuses on training and evaluating a custom CNN model on an image dataset containing 36 classes. Each class contains 2,800 images, for a total of 100,800 images. Each image is 28 × 28 pixels.

## Project Objective

The goal of this project is to build, train, and evaluate a CNN model for image classification. The project includes:

- loading and preparing the dataset
- visualizing the dataset
- preprocessing images and labels
- splitting the dataset into training, validation, and test sets
- building a CNN architecture in PyTorch
- training the model using different optimizers
- applying improvement techniques such as dropout, data augmentation, early stopping, regularization, or learning rate scheduling
- evaluating performance using multiple metrics

## Dataset Information

- **Type:** Multi-class image classification dataset
- **Number of classes:** 36
- **Images per class:** 2,800
- **Total images:** 100,800
- **Image size:** 28 × 28

The dataset is organized by folders, where each folder name represents a class label. The notebook uses PyTorch tools such as `ImageFolder` and `DataLoader` to manage the dataset.

## Methods Used

### Data Preparation
- loaded the dataset
- examined dataset statistics
- created visualizations to better understand the data
- normalized pixel values
- converted class labels to numerical indices
- split the data into training, validation, and testing sets

### Model Building
- implemented a custom CNN in PyTorch
- used convolutional, activation, pooling, and fully connected layers
- produced predictions for 36 output classes

### Training and Optimization
- trained the model over multiple epochs
- compared at least two optimizers
- experimented with performance improvement methods such as dropout, augmentation, early stopping, regularization, or learning rate scheduling

### Evaluation
- measured training, validation, and testing accuracy and loss
- plotted accuracy and loss curves
- generated a confusion matrix
- calculated precision, recall, and F1-score
- reviewed misclassified examples for error analysis

## File in This Repository

- `cnn_image_classification.ipynb` — complete notebook containing code, visualizations, training, and evaluation

## Tools and Libraries

- Python
- PyTorch
- torchvision
- NumPy
- pandas
- Matplotlib
- Seaborn
- scikit-learn
- torchinfo
- Jupyter Notebook

## How to View the Project

1. Open the notebook file in this repository:
   `cnn_image_classification.ipynb`
2. Read through the cells to see the workflow from data preparation to evaluation.


