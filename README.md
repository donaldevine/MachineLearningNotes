# Machine Learning Notes

## Introduction
* Machine Leaning outputs probabilities

## Supervised Learning

* Supervised Learning: Use training data with labels.

* This Training Data trains a model.

* Training Data that has been labelled -> Train  with a classifier -> produces a model.

* Once that Model is in place you can give it an unknown input and it can make conclusions.

## Supervised learning categories
There are 2 Supervised learning categories:
* Regression
* Classification

### Regression
* Prediction
* Map input variables to some continuous function

### Classification
* Classify data
* Map data into discrete categories

## Unsupervised learning

* Unsupervised learning is the training of machine using information that is neither classified nor labeled and allowing the algorithm to act on that information without guidance.

# TensorFlow.js

* TensorFlow.js is a rewrite of Tensorflow in JavaScript.

TensorFlow.js combines:

* Core API - low level
* Layers API - higher level abstraction
* Pre-trained models are available [here](https://www.tensorflow.org/js/models). 

# Neural Networks

 ## Simple example (2 inputs, one output):

* Each input has a feature and a weighting (constant).
* Multiply feature by weighting for each input
* Add the results.
* Pass them through an Activation Function. 
* The result is the output.


# Back Propagation 
* How do you tune the weights so that you get the correct output?
* This involves you telling the system how wrong it is.
* You pass the same data in and adjust the weights until you get the correct ouput.

