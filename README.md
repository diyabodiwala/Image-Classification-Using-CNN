# Image-Classification-Using-CNN

The CIFAR-10 Dataset is an important image classification dataset. It consists of 60000 32x32 colour images in 10 classes (airplanes, automobiles, birds, cats, deer, dogs, frogs, horses, ships, and trucks), with 6000 images per class. There are 50000 training images and 10000 test images.

## The GOALS of this project are to:

Implement different Convolutional Neural Networks (CNN) classifiers using GPU-enabled Tensorflow and Keras API
Compare different CNN architectures


## Tools:

GPU-enabled Tensorflow

Keras API

## Library used for processing CIFAR-10 dataset:

Keras is a high-level neural networks API, which runs on Python and uses TensorFlow in the background. It allows for fast prototyping.

## Convolution Neural Network:

CNNs are one of the most commonly used Neural Networks for Image Classification and Recognition. This is the technique that we are going to use on the CIFAR-10 dataset to classify images in one of the 10 categories.
CNN has 4 steps:
1. Convolution
2. Activation Function
3. Pooling
4. Fully Connected Layer - Dense Layer

## Model 1:
Parameters Used :

Number of convolution layers: 5
Number of pooling layers: 1
Number of dropout layers: 1
Activation Function: tanh
Optimizer: Adamax
Kernel Initialization: 
random-normal 
Epochs-50
Batch-size : 32

Accuracy: 79.72%
Validation Accuracy: 62.14%

Loss:0.579
Validation Loss:0.6214
![image](https://github.com/diyabodiwala/Image-Classification-Using-CNN/assets/83166513/9a67af0e-fce0-4ab4-a81b-28be24087ede)
![image](https://github.com/diyabodiwala/Image-Classification-Using-CNN/assets/83166513/c1ad4de4-c6d5-485b-8ee2-659432b46547)


