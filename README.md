# Brain Tumor Classification using MRI Images

## Overview
This project aims to classify MRI images of the brain to predict the presence and type of tumor using Convolutional Neural Networks (CNN). The model is trained on a dataset consisting of 7033 MRI images labeled with tumor types.

## Dataset Description
The dataset used for training and testing the model can be found [here](insert link to dataset). It contains 7033 MRI images of the brain along with corresponding labels indicating the presence and type of tumor.

## Model Architecture
The CNN model you've provided has a total of 10 layers:

Convolutional layer with 32 filters, kernel size (3, 3), and ReLU activation.
MaxPooling layer with pool size (2, 2).
Convolutional layer with 64 filters, kernel size (3, 3), and ReLU activation.
MaxPooling layer with pool size (2, 2).
Convolutional layer with 128 filters, kernel size (3, 3), and ReLU activation.
MaxPooling layer with pool size (2, 2).
Flatten layer to convert the 2D feature maps into a 1D feature vector.
Dense (fully connected) layer with 128 neurons and ReLU activation.
Dropout layer with a dropout rate of 0.5 to reduce overfitting.
Dense (output) layer with 4 neurons (assuming 4 classes) and softmax activation for classification.
The CNN model architecture consists of [insert number] layers, including convolutional and pooling layers. Details of the architecture can be found in the provided code repository.

## Training Procedure
The model was trained using [insert optimizer], with a batch size of [insert batch size] and for [insert number] epochs. Data augmentation techniques were applied to increase the diversity of the training set.

## Evaluation Metrics
The model was evaluated using accuracy as the primary metric, achieving an accuracy of [insert accuracy] on the test set.
