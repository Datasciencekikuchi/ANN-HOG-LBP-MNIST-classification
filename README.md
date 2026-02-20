# ANN Image Classification with HOG & LBP Features (MNIST)

## Overview
This project implements an end-to-end machine learning pipeline for handwritten digit classification using the MNIST dataset.
Instead of training directly on raw pixels, engineered features are extracted using Histogram of Oriented Gradients (HOG) and Local Binary Patterns (LBP), then an Artificial Neural Network (ANN) is trained on the combined feature vectors.

## Workflow
1. Load MNIST dataset (TensorFlow/Keras)
2. Preprocess and normalize images
3. Extract HOG features
4. Extract LBP features
5. Combine features into a single feature vector
6. Train ANN model
7. Evaluate accuracy and confusion matrix

## Tech Stack
Python, TensorFlow/Keras, scikit-image, scikit-learn, NumPy, Matplotlib, Seaborn

## How to Run
```bash
pip install -r requirements.txt
