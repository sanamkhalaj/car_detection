# Car Detection

A machine learning project for detecting cars from images.

## Overview

This project uses image processing and deep learning techniques to classify images and detect cars.

## Technologies

- Python
- OpenCV
- NumPy
- TensorFlow / Keras
- Scikit-learn

## Data Preprocessing

The images are:
- Resized to 64×64 pixels
- Converted to grayscale
- Shuffled before training
- Encoded using LabelEncoder

## Model

A Sequential neural network is used for image classification, including Flatten and Dense layers.

## Project Workflow

1. Load images from the dataset
2. Preprocess and resize images
3. Convert images to grayscale
4. Encode the labels
5. Split the data into training and testing sets
6. Train the neural network
7. Evaluate the model

## Results

The model achieved an accuracy of **98%** on the test dataset.

## Author

Sanam Khalaj
