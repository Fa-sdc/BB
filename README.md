# End to end Dog Breed multi-classification

This notebook builds an end to end multi class image classifier using TensorFlow 2.50 and TensorFlow Hub.

## 1. Problem definition

Identifying a dog breed given an image of a dog.

When I am sitting at the cafe and I take a photo of a dog, I want to know what breed of dog it is.

## 2. Data

The data we are using is from Kaggle's dog breed identification competition, available in the link below.

https://www.kaggle.com/c/dog-breed-identification/data

## 3. Evaluation

For each image in the test set, we must predict a probability for each of the different breeds.
Find more on evaluation in the link:

https://www.kaggle.com/c/dog-breed-identification/overview/evaluation

## 4. Features

Informations about the data:
* We are dealing with images(unstructured data), so it is best to use deep learning & transfer learning.
* There are 120 breed of dog, this means there are 120 different classes.
* There are arround 10,000+ images in the training set(these images have labels).
* There are arround 10,000+ images in the test set(these images does not have labels because we will want to predict them).
