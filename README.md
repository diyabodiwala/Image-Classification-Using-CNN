# PixeloMagic: Neural Image Classifier
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

## Model 2:

Parameters Used :

Number of convolution layers: 5
Number of pooling layers: 1
Number of dropout layers: 1
Activation Function: reLu
Optimizer: RMSProp
Kernel Initialization: 
random_normal
Epochs-50
Batch-size : 500 

Accuracy: 78.36%
Validation Accuracy:62.73% 

Loss:0.6106
Validation Loss:1

![image](https://github.com/diyabodiwala/Image-Classification-Using-CNN/assets/83166513/26b73ce3-79ac-469e-a4ad-d47dea0564c5)
![image](https://github.com/diyabodiwala/Image-Classification-Using-CNN/assets/83166513/5c9d4e39-cb4c-44c4-a0f2-ad9ae8b9e294)

## Model 3:
Parameters Used :

Number of convolution layers: 8
Number of pooling layers: 1
Number of dropout layers: 1
Activation Function: reLU
Optimizer: Adamax
Kernel Initialization: 
glorot_uniform
Epochs-100
Batch-size : 500 

Accuracy: 93.01%
Validation Accuracy: 72.93%

Loss:0.2222
Validation Loss:1.1419

![image](https://github.com/diyabodiwala/Image-Classification-Using-CNN/assets/83166513/b15daf9c-3ebc-4768-b79e-0c185720de6c)
![image](https://github.com/diyabodiwala/Image-Classification-Using-CNN/assets/83166513/2e1bb13d-e37b-4caa-bff1-345d89f03059)

## Model 4:

Parameters Used :

Number of convolution layers: 7
Number of pooling layers: 3
Number of dropout layers: 3
Activation Function: reLu
Optimizer: Adamax
Kernel Initialization: 
uniform
Epochs-100
Batch-size : 500 

Accuracy: 86.33%
Validation Accuracy: 80.17%

Loss:0.376
Validation Loss:0.8017

![image](https://github.com/diyabodiwala/Image-Classification-Using-CNN/assets/83166513/bed6ccdd-b289-495c-a700-db608ff56ed6)
![image](https://github.com/diyabodiwala/Image-Classification-Using-CNN/assets/83166513/e117455a-d8f9-4f71-bd8d-aade7d2afd7f)

## Model 5:

Parameters Used :

Number of convolution layers: 15
Number of pooling layers: 3
Number of dropout layers: 4
Activation Function: relu
Optimizer: Adam
Kernel Initialization: 
glorot_uniform
Epochs-200
Batch-size : 100

Accuracy: 84.43%
Val_Acc : 82.30%

Loss: 0.1960
Validation-Loss:0.452

![image](https://github.com/diyabodiwala/Image-Classification-Using-CNN/assets/83166513/7f6c09ea-fe55-4baa-b23a-66b1a604daa4)

![image](https://github.com/diyabodiwala/Image-Classification-Using-CNN/assets/83166513/2ebe7b0b-357d-4ba5-b5df-dae55431152f)

Model 6:
