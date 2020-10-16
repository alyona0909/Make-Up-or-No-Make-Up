# Make-Up-or-No-Make-Up

In this notebook, we're going to predict whether or not person on image having makeup by training a neural network that classifies images.

## Data 

The data we're using is from Kaggle : https://www.kaggle.com/petersunga/make-up-vs-no-make-up

This dataset `makeup-or-no-makeup.zip` contains 2 folders:

* makeup - 1062 images of people wearing makeup
* no_makeup - 444 images of people not wearing makeup

Can deep learning determine if a person is wearing makeup or not?


## Content

* `makeup-or-no-makeup.ipynb`

This file builds a neural network that classifies images.
 
Before modeling, we'll turn all images to Tensors.

We're using Mobile Net V2 classification model : https://tfhub.dev/google/imagenet/mobilenet_v2_130_224/classification/4.
