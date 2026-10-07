# CNN-Binary-Image-Classifier
CNN for binary image classification (cats vs dogs) built with Tensorflow/Keras, reaching a 80% test accuracy.
A simple convolutional neural network project built to classify pictures of animals using the cats and dog dataset. This project was created as a part of my learning journey into Deep Learning and Neural Networks, with focus on understanding on how a neural network processes image data and learns to recognize patterns.

## Project Overview
The goal of this project is to build a cnn model  capable of predicting and identifying image data.

## Mode Architecture
The model follows a simple convolutional neural network structure:  Image - Convo 2D - Max pooling 2D - Convo 2D - Max pooling 2D - Flatten - Dense Layer -Dropout Layer -Output Layer - Prediction (0 or 1). The output layer contains 2 neurons, corresponding to the 2 possible outcomes  , the neuron with the highest output represents the model predicted image

## Results 
As seen in the code, accuracy was 80% . This is noticed after the 5Th epoch , where the model now starts memorizing the images instead of learning, so to curb that we can use 
1. Data Augmentation
2. Early Stopping
3. Transfer Learning 

## Technologies Used
Python
TensorFlow/Keras
Numpy
Matplotlib
Jupyter Notebook/Google Colab
Results
The model was able to learn the patterns present in the handwritten digit images and classify previously seen images.

## Author
Kamsi Onodingene
