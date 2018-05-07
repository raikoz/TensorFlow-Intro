# TensorFlow Intro
This is all about building a handwritten digit image classifier in Python in under 40 lines of code (not including spaces and comments). Using the popular library TensorFlow to do this. 

## Overview

This project helps train a classifier to recognize handwritten character images [MNIST digits](http://yann.lecun.com/exdb/mnist/). It uses logistic regression as it's model and trains on a small MNIST dataset before testing the trained model on it. Can view the constructed data flow graph using Tensorboard in your browser after training.


## Dependencies

TensorFlow (https://www.tensorflow.org/versions/r0.10/get_started/os_setup.html#pip-installation)

Use [pip](https://pypi.python.org/pypi/pip) to install any missing dependencies
<p>
<img src="https://camo.githubusercontent.com/d440ac2eee1cb3ea33340a2c5f6f15a0878e9275/687474703a2f2f692e7974696d672e636f6d2f76692f3051493378675875422d512f687164656661756c742e6a7067" height="220px" align="left">
</p>

## Basic Usage

1. Run 
```
python board.py
``` 
to train the model. It will download & split the MNISt dataset into training and testing data. Then it will train a logistic regression model on the data. Lastly, it will test the trained model on the test set.

2. You can visualize the model in tensorboard by running, yu need AVX2 enabled through a GPU, or simply visualize through localhost.
```
tensorboard --logdir=LOCATION_ON_YOUR_COMPUTER
```
That's it!

## Credits

Credit for the vast majority of code here goes to Google and GitHub of TensorFLow.
