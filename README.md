# -Car-vs-Bike-Image-Classification-Project

Project Summary
---------------
This project uses a Convolutional Neural Network (CNN) to classify images as either car or bike, based on the Car-Bike-Dataset.zip.

Dataset
File: Car-Bike-Dataset.zip
Contains two categories: car and bike images.

Steps Followed
---------------

1.Unzip the dataset

2.Import libraries

tensorflow

ImageDataGenerator from tensorflow.keras.preprocessing.image

3.Image preprocessing

Rescale pixel values

Apply shear (tilting), zoom, and other augmentations

4.Create training and test sets

5.Build CNN model

Sequential model

Add convolutional and pooling layers:

1st Conv2D layer: 32 filters (3x3)

1st MaxPooling2D layer: 2x2

2nd Conv2D layer: 32 filters (3x3)

2nd MaxPooling2D layer: 2x2

Flatten layer to convert image to 1D

Fully connected Dense hidden layer

Output layer for binary classification

6.Compile the model

7.Train the model

8.Test on new images

Load and preprocess image

Convert to array, reshape, and predict

9.Interpret prediction

Use train_set.class_indices

Use if-else to display result: Car or Bike


Technologies Used
-----------------
1.Python

2.TensorFlow / Keras

 Output
 ------
The model is able to predict whether a new image is of a car or a bike.





