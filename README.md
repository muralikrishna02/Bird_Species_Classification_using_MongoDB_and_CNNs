# Bird Image Classification using MongoDB and CNNs

## Overview

This project is focused on creating a Bird Image Classification system using a Convolutional Neural Network (CNN). The objective is to accurately classify bird species based on images. The dataset comprises images of various bird species, and the trained model can predict the species of a given bird image.

## Dependencies

Ensure you have the following dependencies installed:

- Python 3
- MongoDB
- TensorFlow
- OpenCV
- NumPy
- Matplotlib
- scikit-learn
- pymongo


## Data Collection and Storage
Bird images are stored in MongoDB using GridFS. This uploads images from a local directory to the MongoDB database.

## Data Preprocessing
Images are loaded from MongoDB, resized, and flattened. Categorical labels are mapped to numerical values, and the dataset is split into training and testing sets.

## Model Architecture
The CNN model is designed using TensorFlow and Keras. The architecture includes convolutional layers, flattening, and dense layers. The model is compiled using the Adam optimizer and sparse categorical crossentropy loss.

## Training the Model
The model is trained using the training dataset. The training process is visualized and monitored for accuracy and loss.

## Model Evaluation
The model's performance is evaluated using a test dataset. Evaluation metrics such as accuracy and loss are analyzed.

## Predictions
The trained model is used for making predictions on new bird images. 
