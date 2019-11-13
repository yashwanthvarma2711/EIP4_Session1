# EIP4_Session1
Assignment of Session 1 - Basics of Convolution Neural Networks

# Score - 99.27%

print(score) 

[0.03688484263069972, 0.9927]

# Own Definitions

## 1. convolution :  
It is a process of applying a filter repeatedly over an input image with an intention to extract features from the image.

## 2. Filters / kernels : 
It is an operator which extracts features from input image by looking at part of it. Generally the size of kernel is smaller than input and the type of operation applied is dot product.

## 3. Epochs : 
Passing the complete training data to a network once is an epoch.

## 4. 1X1 convolution : 
An operation, in which an input image is convolved with a 1X1 filter, through which the number of features can be changed by keeping the same height and width. 

## 5. 3X3 convolution: 
An operation, in which an input image is convolved with a 3X3 filter, to extract information like vertical, horizontal edges by leveraging information at neighborhood.

## 6. Feature maps : 
The set of convolved features obtained by the repeated application of filter over input image.

## 7. Activation Function : 
A function which adds nonlinearity to obtain the needed features.

## 8. Receptive Field : 
The area of the input layer contributing to one pixel of the next layer. Local receptive field is the size of the kernel.

