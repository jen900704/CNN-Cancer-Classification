# CNN Cancer Classification

This repository contains a convolutional neural network model for classifying metastatic cancer in histopathology image patches. The dataset is from the Kaggle Histopathologic Cancer Detection challenge.

## Overview

The objective of this project is to determine whether a pathology image contains cancerous tissue or non cancerous tissue.
The notebook includes data loading, exploratory analysis, preprocessing, model construction, training, and evaluation.

The main notebook is located in the notebooks directory.

## Repository Structure

notebooks  
CNN_Cancer_Classification.ipynb  

data  
Placeholder only. The dataset is not included because of its size and licensing restrictions.

## Method Summary

The model is a convolutional neural network composed of convolutional layers, max pooling layers, a fully connected layer with dropout, and a final sigmoid output layer.

Training uses the Adam optimizer and binary cross entropy loss.
The images are resized to 96 by 96.
Data augmentation is performed using ImageDataGenerator.

## Results

The notebook presents training and validation accuracy and loss.
The evaluation includes the ROC curve and the AUC score.

## Dataset

Dataset name  
Kaggle Histopathologic Cancer Detection

The dataset is not included in this repository. It must be downloaded directly from Kaggle and placed in the data directory if needed.

## Notes

This project serves as a baseline model for cancer detection using convolutional neural networks.
Possible improvements include deeper architectures, transfer learning, additional preprocessing, and handling class imbalance.

## Author

Hsiang Chen Yeh
