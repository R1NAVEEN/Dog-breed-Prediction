# End-to-end Multi-class Dog Breed Classification

This notebook builds an end-to-end multi-class image classifier using TensorFlow 2.0 and TensorFlow Hub.

##  1. Problem

Identifying the breed of a dog given an image of a dog.

When im sitting at the cafe and i take a photo and want to know what breed it is.

## 2. Data

the data is taken from kaggale
https://www.kaggle.com/c/dog-breed-identification

## 3. Evaluation

The evaluation is a file with prediction probabilities for each dog breed of each test image.

## 4. Features

Some information about the data:

* we're dealing with images (unstructured data) so it's probably best we use deep learning' transfer learning.

* There are 120 breeds of dogs (this means there are 120 different classes).

* There are around 10,000+ images in the training set(these images have lables)..

* There are saround 10,000+ images in the test set (these  images have no labesls because we want to predict them).
