# CodeAlpha_HandWritten_Text_Recognition
Handwritten Text Recognition - Machine Learning Project - CodeAlpha Intenship

This project implements a handwritten text recognition system using convolutional neural networks (CNNs) with TensorFlow and Keras. The model is trained to classify images of handwritten characters into predefined categories.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Training](#training)
- [Evaluation](#evaluation)
- [Visualizations](#visualizations)

## Overview
This project uses a dataset of grayscale images of handwritten English characters. A CNN is used for image classification, with data augmentation applied to improve model generalization. The model's performance is tracked through training and validation accuracy and loss metrics.

## Dataset
* The dataset was downloaded from Kaggle (https://www.kaggle.com/datasets/dhruvildave/english-handwritten-characters-dataset)
* The dataset used in this project is the "English Handwritten Characters Dataset" provided by Dhruvil Dave on Kaggle. It contains images of handwritten English characters and is used for training and evaluating the handwritten text recognition model.

* **Source:** English Handwritten Characters Dataset
* **Size:** Approximately 200,000 images of handwritten English characters.
* **Format:**
    * **Images:** Grayscale PNG images of handwritten English characters.
    * **CSV File:** english.csv - contains image file paths and corresponding labels.

## Training:
1. Images are preprocessed (resized to 32x32 and normalized).
2. Data augmentation is applied.
3. A CNN model is built and trained with early stopping, model checkpoint, and learning rate reduction callbacks.

## Evaluation
1. The model's performance is evaluated on the validation set.
2. Validation loss and accuracy are printed to the console.

## Visualizations:
* Training and validation loss and accuracy are plotted and displayed.
* Sample predictions are visualized with true and predicted labels.

