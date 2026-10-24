# EN3160 Assignment 3 - Neural Networks

This repository contains the implementation and results for Assignment 3 of **EN3160 - Image Processing and Machine Vision**.

### Assignment Topics

1. **Dense Neural Network Implementation**
   - Implementation of a single-layer dense network with manually computed forward and backward passes
   - Extension to a two-layer dense neural network with a 100-node sigmoid hidden layer
   - Cross-entropy loss implementation
   - Manual gradient computation and parameter updates
   - Training and test accuracy evaluation on the CIFAR-10 dataset
   - Analysis of training performance over 10 epochs

2. **LeNet-5 for MNIST Classification**
   - Implementation of the LeNet-5 convolutional neural network using PyTorch
   - Training and evaluation on the MNIST handwritten digit dataset
   - Training and test accuracy measurement after 10 epochs
   - Per-epoch training and test loss tracking
   - Per-epoch training and test accuracy tracking
   - Confusion matrix analysis of classification performance

3. **Modern Convolutional Neural Network**
   - Implementation of a compact three-layer CNN using PyTorch
   - Integration of batch normalization and dropout
   - Training and evaluation under the same conditions as LeNet-5
   - Comparison of training and test accuracy and loss
   - Visualization of per-epoch performance
   - Confusion matrix analysis and comparison with LeNet-5

4. **Transfer Learning with ResNet18**
   - Loading a ResNet18 model pretrained on ImageNet-1K
   - Preparation of the Hymenoptera (ants and bees) dataset
   - Fine-tuning the pretrained network for binary image classification
   - Using ResNet18 as a fixed feature extractor
   - Training and evaluation of the classification layers
   - Comparison of the two transfer learning approaches
   - Analysis of classification performance on the validation dataset
