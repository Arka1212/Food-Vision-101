# Food-Vision-101🍔👁️
Making Food Vision Big™, using all of the data from the Food101 dataset.


## Problem Statement
Predict food image out of 101 category or classes of foods.

## Objective
I am going to build Food Vision Big™, using all of the data from the Food101 dataset. All 75,750 training images and 25,250 testing images will be taken into consideration. This time I have got the goal of beating DeepFood, a 2016 paper which used a Convolutional Neural Network trained for 2-3 days to achieve 77.4% top-1 accuracy.

## Data
The original data came from the TensorFlow Datasets (TFDS), read the guide: https://www.tensorflow.org/datasets/overview.

## Steps
* Using TensorFlow Datasets to download and explore data
* Creating preprocessing function for our data
* Batching & preparing datasets for modelling (making our datasets run fast)
* Creating modelling callbacks
* Setting up mixed precision training
* Building a feature extraction model
* Fine-tuning the feature extraction mode

Knowing this, in order to use 'mixed precision training' we need access to a Tesla T4 (from within Google Colab) or if we're using our own hardware, our GPU needs a score of 7.0+ (see here: https://developer.nvidia.com/cuda-gpus).
