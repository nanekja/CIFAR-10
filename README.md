# CIFAR-10
Various experimentation on CIFAR-10 dataset


## Classifying images of everyday objects
In this repository, several approaches has been experimented on CIFAR-10 dataset using Pytorch. During this I will explore the CIFAR-10 dataset in : https://www.cs.toronto.edu/~kriz/cifar.html

The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.

Here is a batch of 128 images from CIFAR-10 dataset:

![Screenshot](https://github.com/nanekja/CIFAR-10/blob/master/images/cifar_10.png)



| Model | Linear/Conv Layers | Optimizer | Batch Size | Learning Rate | Parameters | Epocs | Time | Validation Accuracy |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Logistic Regression | None | SGD | 128 | 0.05 | 30 k | TBD | TBD | 0.3718| 
| Feed Forward Neural Network | 4 | SGD | 128 | 0.09 - 0.01 | 3.4 M | TBD | TBD | 0.5569 | 
| CNN+FeedForward NN | 12 | Adam | 128 | 0.001 | 5.8 M | TBD | TBD | 0.7675 |
| CNN+FeedForward NN v2 | 12 | Adam | 128 | 0.001 | 23.6 M | TBD | TBD | 0.8915 |
| Vanilla CNN v1 | 16 | Adam | 128 | 0.001 | 1.18 M | TBD | TBD | 0.722 |
| Vanilla CNN v2 | 12 | Adam | 128 | 0.001 | 855 k | 50 | TBD | 0.8382 |
| CNN v1 | 12 | Adam | 400 | 0.01- 0.001 | 855 k | 50 | 24m | 0.8539 |
| CNN v2 | 9 | Adam | 400 | 0.01- 0.001 | 788 k | 50 | 20m | 0.8658 |
