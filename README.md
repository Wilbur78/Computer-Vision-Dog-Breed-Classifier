# Computer Vision Dog-Breed Classifier

### End-to-end Multi-class Dog Breed Classification

This notebook builds an end-to-end multi-class image classifier using TensorFlow 2.0 and TensorFlow Hub.


### 1. Problem

Identifying the breed of a dog given an image of a dog.

When I'm sitting at the cafe and I take a photo of a dog, I want to know which breed of dog it is.


### 2. Data

The data being used is from Kaggle's dog breed identification competition.

https://www.kaggle.com/c/dog-breed-identification/data


### 3. Evaluation

The evaluation is a file with prediction probabilities for each dog breed of each test image.


### 4. Features

Some information about the data:
* We're dealing with images (unstructured data), so it's probably best to use deep learning and transfer learning
* There are 120 breeds of dogs (this means there are 120 different classes).
* There are around 10,000+ images in the training set; around 10,000+ images in the test set as well.
* Training set images have labels
* Some test set images have labels, some of them do not.
