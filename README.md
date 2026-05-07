# part-2-cnn-computer-vision
Computer Vision with CNN
Project Overview

This project involves building a Convolutional Neural Network (CNN) using TensorFlow/Keras to classify grayscale images. The dataset consists of images processed into a $32 \times 32$ pixel format.

How to Run
To replicate this project in Google Colab:

Upload Files: Upload images.zip and labels.csv to the Colab file storage.
Environment Setup: The first cell in the notebook handles unzipping the data into a folder named final_data and matching filenames from the CSV.
Data Preprocessing: The code automatically strips path prefixes from the CSV to match the local image directory and normalizes pixel values to a range of 0 to 1.
Model Training: Run the CNN architecture cell, followed by the training cell. The model is set to train for 15 epochs.
Evaluation: Review the Accuracy and Loss plots generated at the end of the notebook to evaluate model performance.

Model Architecture

The CNN consists of:
Two Conv2D layers for feature extraction (edges and shapes).
Two MaxPooling2D layers to reduce spatial dimensions.
A Flatten layer followed by a Dense (ReLU) layer and a final Softmax output layer for classification.
