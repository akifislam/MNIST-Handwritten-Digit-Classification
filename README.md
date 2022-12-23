# Welcome Myself to Deep Learning & Neural Network

<div align=center>
Handwritten Digit Recognition using Machine Learning and Deep Learning

MNIST is a collection of handwritten digits from 0-9.
Image of size 28 X 28

</div>

# Training (epoch = 15)

<div align=center>
<img src="./Training.png">
</div>

# Prediction Sample

- Test Data : Handwritten Digit of 7
- Prediction : 7 (Success)
  </br>

<div align=center>
<img src="./mnist_prediction_sample.png">
</div>

# Requirements

- Python 3.10
- Keras
- Numpy (+ mkl for Windows)
- Matplotlib
- TensorFlow

```python
import tensorflow as tf
from tensorflow import keras
import matplotlib.pyplot as plt
%matplotlib inline
import numpy as np
```

</br>

# Introduction

MNIST contains 70,000 images of handwritten digits

- 60,000 for training
- 10,000 for testing.
- The images are grayscale, 28x28 pixels
- centered to reduce preprocessing and get started quicker.

Keras is a high-level neural network API focused on user friendliness, fast prototyping, modularity and extensibility. It works with deep learning frameworks like Tensorflow, Theano and CNTK, so we can get right into building and training a neural network without a lot of fuss.

## Description

This is a 5 layers Sequential Convolutional Neural Network for digits recognition trained on MNIST dataset. I chose to build it with keras API (Tensorflow backend) which is very intuitive.

## Accuracy

It achieved 92.61% of accuracy with this CNN trained on my mac without any external GPU, which took me about a minute.

</br>

<div align=center>
<b> Made with ❤️ by Akif Islam </b>
</div>
