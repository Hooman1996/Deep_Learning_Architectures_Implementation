# Deep_Learning_Architectures_Implementation
- This repository contains from-scratch implementations of four foundational convolutional neural network architectures in both TensorFlow and PyTorch

  - LeNet-5: The pioneering CNN architecture for digit recognition

  - VGG: Known for its simplicity and depth using 3x3 convolutions

  - GoogleNet (Inception): Introduced the inception module with parallel convolutions

  - ResNet: Revolutionized deep learning with residual connections

- Key Features
  ✅ Dual Framework Implementation: All models available in both TensorFlow and PyTorch
  ✅ From-Scratch Implementation: No reliance on pre-built models (except basic layers)
  ✅ Modular Design: Easy to adapt and extend for your projects
  ✅ Training Scripts: Example training pipelines for each architecture
  ✅ Pre-trained Weights: Available for quick experimentation

Models Overview
1. LeNet-5
The first successful CNN architecture (1998) for digit recognition with:

Two convolutional layers

Two subsampling (pooling) layers

Three fully connected layers

2. VGG
The uniform architecture (2014) that showed depth matters with:

Only 3×3 convolutions

Multiple variants (11 to 19 layers)

Simple yet effective design

3. GoogleNet (Inception)
The efficient architecture (2014) featuring:

Inception modules (parallel convolutions)

1×1 convolutions for dimensionality reduction

Auxiliary classifiers for training

4. ResNet
The breakthrough architecture (2015) that enabled very deep networks with:

Residual blocks with skip connections

Batch normalization after each conv layer

Variants from 18 to 152 layers

Requirements
Python 3.7+

TensorFlow 2.x / PyTorch 2.+

CUDA capable GPU (recommended)

Model	Framework	Top-1 Accuracy (CIFAR-10)	Parameters
LeNet-5	TensorFlow	78.2%	61k
VGG-16	PyTorch	92.1%	15M
GoogleNet	TensorFlow	93.4%	6.8M
ResNet-50	PyTorch	94.6%	25.5M
Note: Results may vary based on training hyperparameters


Acknowledgments
Original papers from LeCun, Simonyan, Szegedy, and He

TensorFlow and PyTorch documentation

Community implementations that inspired this work

Alladin pearson
