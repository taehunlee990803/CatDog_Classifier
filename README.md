# Cat_or_Dog
Convolutional Neural Network (CNN) for Cat and Dog Image Classification
Overview
This Python script implements a Convolutional Neural Network (CNN) using TensorFlow and Keras for the classification of cat and dog images. The CNN is trained on a dataset consisting of labeled cat and dog images.

Contents
Model Architecture

The CNN architecture consists of convolutional layers with ReLU activation, max-pooling layers, flattening layer, fully connected layers, and an output layer with sigmoid activation.
Training

The model is compiled using the Adam optimizer and binary crossentropy loss. It is trained on a training set and evaluated on a test set for 25 epochs.
Making Predictions

After training, the script includes a section for making predictions on a single image using the trained model. The prediction result is displayed as either 'cat' or 'dog'.
Dependencies

Ensure you have TensorFlow and Keras installed in your Python environment.
