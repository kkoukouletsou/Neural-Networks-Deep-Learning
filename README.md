**Neural Network** Models for **CIFAR-10** and **MNIST**

This repository contains various implementations of machine learning models and techniques applied to the CIFAR-10 and MNIST datasets. The models include traditional algorithms like k-Nearest Neighbors (kNN), Support Vector Machines (SVM), Radial Basis Function Neural Networks (RBFNN), as well as deep learning models such as Convolutional Neural Networks (CNN), Multi-Layer Perceptrons (MLP), and Autoencoders.

Additionally, this repository explores hybrid models that combine CNN as feature extractors with SVM or RBFNN for classification. It also includes an Autoencoder model and a Convolutional Autoencoder for reconstructing MNIST images, followed by CNN-based digit recognition on the reconstructed images.

Models Implemented for CIFAR-10 **Multiclass Classification Problem** (One vs The Rest Approach)
1. k-Nearest Neighbors (kNN)
2. Nearest Centroid Classifier (NCC)
3. Convolutional Neural Network (CNN)
4. Multi-Layer Perceptron (MLP)
5. Support Vector Machine (SVM)
6. Radial Basis Function Neural Network (RBFNN)
7. Hybrid CNN + SVM
8. Hybrid CNN + RBFNN

Models Implemented for MNIST **Image Reconstruction** and **Digit Recognition** 
1. Autoencoder
2. Autoencoder with Convolutional Layers
3. CNN for Digit Recognition

*** hybrid approach where CNNs are used as feature extractors, and either SVM or RBFNN is used for classification. This combination leverages the power of CNNs for extracting features and the effectiveness of SVM or RBFNN for classification.
