# Strawberry Disease Classification using Convolutional Neural Networks
## Overview
This project focuses on classifying different diseases affecting strawberry plants using Convolutional Neural Networks (CNNs). The dataset consists of images of strawberry plants with various diseases, and the CNN model is trained to accurately predict the disease class.

## Project Structure
### Data Preprocessing
The project starts with data preprocessing using the splitfolders library to organize the dataset into training, validation, and test sets. ImageDataGenerator from Keras is utilized for augmenting the training data.

### Building the CNN Model
The Convolutional Neural Network architecture is designed using TensorFlow and Keras. The model consists of convolutional layers, max-pooling layers, a flatten layer, and dense layers for classification.

### Training the CNN Model
The model is compiled using Adam optimizer and categorical cross-entropy loss. Training is performed using the fit method with the specified number of epochs.

### Model Evaluation and Prediction
The trained model is evaluated on the test set, and predictions are made on a sample test image.

### Visualizing Training History
The training and validation accuracy/loss history is visualized using matplotlib
