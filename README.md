# CIFAR-10
Various experimentation on CIFAR-10 dataset


## Classifying images of everyday objects
In this repository, several approaches has been experimented on CIFAR-10 dataset using Pytorch. During this I will explore the CIFAR-10 dataset in : https://www.cs.toronto.edu/~kriz/cifar.html

The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.

Here is a batch of 128 images from CIFAR-10 dataset:

![Screenshot](https://github.com/nanekja/CIFAR-10/blob/master/images/cifar_10.png)



| Model | Layers | Optimizer | Batch Size | Learning Rate | Validation Loss | Validation Accuracy |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | 
| Logistic Regression | None | SGD | 128 | 0.05 | 1.792 | 0.3718 | 
| Feed Forward Neural Network | 4 | SGD | 128 | 0.05 | 1.331 | 0.5569 | 
