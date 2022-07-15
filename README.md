# VGG-11 on CIFAR-10 Dataset

## About
This is the implementation of VGG-11 model using PyTorch. The goal is to build a VGG model from scratch using PyTorch modules which is
then trained on CIFAR-10 Dataset. After training for 20 epochs, the accuracy for testing set is around 80%. The parameters are then saved for practicing purposes. 

## VGG Model
VGG stands for Visual Geometry Group. It is a Convolutional Neural Network(CNN) architecture with convolution blocks followed by 
fully-connected layers. VGG-11, for example, has 8 convolutional layers and 3 fully-connected layers, hence it is called VGG-11. The original paper can be found
[here](https://arxiv.org/abs/1409.1556){:target="_blank"}.  

## Dataset
CIFAR-10 dataset consists 60000 32x32 RGB images of 10 different classes. There are 50000 training images and 10000 test images. The 
classes are :
1. Airplane
2. Automobile
3. Bird
4. Cat
5. Deer
6. Dog
7. Frog
8. Horse
9. Ship
10. Truck   