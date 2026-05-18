# Campus Vegetation Classifier

A traditional computer vision and machine learning project that classifies campus vegetation species using handcrafted image features and an SVM classifier.

## Overview

This project builds an end-to-end plant classification pipeline using manually collected campus vegetation images. The model classifies images into 10 plant categories using HSV color histogram features and a Support Vector Machine classifier.

## Features

- Manually collected plant image dataset
- 10 vegetation classes
- Training/validation split
- Image resizing and preprocessing
- HSV color histogram feature extraction
- Normalized feature vectors
- SVM classifier with RBF kernel
- Confusion matrix and classification report
- Upload-based prediction interface in Google Colab
- Real-world testing and error analysis

## Results

- Validation accuracy: approximately 90%
- Strong performance on controlled validation images
- Lower robustness with cluttered backgrounds, multiple plants, and lighting shifts

## Technologies Used

- Python
- OpenCV
- NumPy
- scikit-learn
- Matplotlib
- Google Colab
- Computer Vision
- Machine Learning

## Report

[Assignment Report](Assignment2_Report_25142309x_PATEL_Diya.pdf)

## Limitations

The model relies primarily on color histograms, so it may confuse plants with similar color distributions and does not fully capture leaf shape, texture, or spatial structure.

## What I Learned

This project strengthened my understanding of image preprocessing, handcrafted feature extraction, traditional machine learning, model evaluation, and real-world robustness testing.
