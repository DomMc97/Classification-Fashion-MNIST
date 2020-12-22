# Classification of the Fashion-MNIST Dataset

## Overview
Project which expands on the third coursework of the Methods for Data Science module I took as part of my MSc Applied Mathematics at Imperial College London.

In this task I firtsly found k-means unsupervised clusterings of the image data set. I then went on to use both Convolutional and Multi-Layer-Perceptron Neural networks for the supervised classification of the dataset obtaining an optimised accuracy of 90%.

## Data
The dataset I worked with is the Fashion-MNIST dataset a collection of images of fashion items sold by Zalando. Each sample is originally a grayscale image with 28x28 pixels. Each pixel has a value of the grayscale between 0 and 255. In some of my tasks below, the images will be described as p-dimensional vectors  (p=28^2 = 784) ; in other tasks, the images will need be considered as 28x28 matrices.

Each image in the dataset belongs to one of C=10 classes with the following labels: T-shirt/otp, Trousers, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag and ankle boots.

The dataset consists of 60000 images in the training set and 10000 additional images.

## Clustering

A notebook containing the K-means unsupervised clustering of the Fashion MNIST dataset.

## Classification

A notebook containing the classification of the Fashion MNIST dataset using a Multi Layer Perceptron(MLP) and a Convolution Neural Network (CNN).
