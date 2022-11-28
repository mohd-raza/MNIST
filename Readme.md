# MNIST Handwritten Digit Recogintion using Pytorch
The MNIST database (Modified National Institute of Standards and Technology database) is a large collection of handwritten digits. It has a training set of 60,000 examples, and a test set of 10,000 examples. It is a subset of a larger NIST Special Database 3 (digits written by employees of the United States Census Bureau) and Special Database 1 (digits written by high school students) which contain monochrome images of handwritten digits. The digits have been size-normalized and centered in a fixed-size image. The original black and white (bilevel) images from NIST were size normalized to fit in a 20x20 pixel box while preserving their aspect ratio. The resulting images contain grey levels as a result of the anti-aliasing technique used by the normalization algorithm. the images were centered in a 28x28 image by computing the center of mass of the pixels, and translating the image so as to position this point at the center of the 28x28 field.

## In this project
* MNIST Dataset is loaded which consist of numerical values.
* Dataset has been preprocessed by using normalization and splitting into train and test split
* A neural network of 5 hidden layer has been hard coded using NN module of pytorch, and dropout layers hava also been implemented.
* The model is trained on 25 Epochs, Adam's Optimizer with an intial learning rate of = 0.001 and train loss and test loss has been calculated
* The accuracy achieved was 97.8%
* The prediction on test dataset was implemented along with the graph of the handwritten digit.

## Modules Used:
* Pandas
* Numpy
* Matplotlib
* Torch
* Sckit-Learn


![image](https://user-images.githubusercontent.com/91888013/204275087-5c2f0d7d-f194-4b4c-bc28-19a4708bebc1.png)

  
