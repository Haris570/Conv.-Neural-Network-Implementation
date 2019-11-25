# Implementation of Convolutional Neural Network (CNN) with Keras  

All the parameters will be configured from the json file.

This project can be used on any type of dataset:

DataPreparation module can be used for data augmentation as well as extraction. This module contains the functionality to preprocess raw data and create a normalized, balanced dataset.

Train CNN module is used to train the model with optimized parameters. The manipulation in the layers can be performed if the training data is sparse or dense. After the completion of training process this module will save the trained model onto the local disk on the computer. 


Test CNN module is used to evaluate the trained model with test data. Once the testing phase is finished, it will also generate the confusion matrix.

The required libraries and Python version to run this code are as mentioned below. To download them please reffer to their official websites if needed.

-Python: '3.6' -Tensorflow Version: '1.9.0' -Keras: '2.2.2' -Opencv: '3.4.2' -sklearn: '0.20.0' -matplotlib: '2.2.2' -numpy: '1.15.4'
