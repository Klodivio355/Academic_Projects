# Academic Projects
This directory contains links to projects undertaken at The University Of Sheffield. These projects, all together, represent my area of interest.


## Adaptive Intelligence

This module assignment consisted in 2 tasks:
- Assignment 1 : Multi-class classification on the famous MNIST dataset using Multi-layer Perceptrons. The whole implementation is in Python, primarly using Numpy. The system includes the implementation of different layer dimensions, regularisation etc..
- Assignment 2 : Multiple Deep Reinforcement Learning were applied to an autonomous navigation system. An implementation of SARSA has been carried out as well an Eligibity-Trace feature. Again, this implementation is relatively low-level as it is in Numpy.


## Mutimodal Pneumonia Etiology Classification

Using the large and complex medical dataset MIMIC-IV along with the linked X-ray dataset MIMIC-CXR. We provide a complete, research oriented framework that allows for a multimodal classification (using both X-rays as images and Static Data) of pneumonia 2 most common causes (i.e. etiologies) being Viral and Bacterial. Such difference is depicted below :

<p align="center">
  <img src="https://www.mdpi.com/applsci/applsci-10-00559/article_deploy/html/images/applsci-10-00559-g010-550.jpg" />
</p>

This study made it to a paper that was submitted to the [Medical Image Understanding and Analysis 2022](https://www.miua2022.com) conference by The University of Cambridge. The paper is currently under review and is available along with the project's description in the repository.

## Spectral Clustering with Fairness Constraints

This dissertation was originally intended to replicate the results found in the [paper](https://arxiv.org/abs/1901.08668) by Kleindessner et. al (2017). A further objective was to put the algorithms incorporating Fairness Constraints within the Spectral Clustering cut objective function introduced in this paper to the test using synthetic and real-world datasets, and to bring these to different levels of perturbations similar to how real graph data behaves in real-life circumstances. Addtionally, a literature survey has been performed to assess the the whys and wherefores of Fairness in Artificial Intelligence.
The repository a series a standalone notebooks containing :
- Synthetic Data (using LFRs and SBMs) 
- Real-world Graph Data (DrugNET / FacebookNET / FriendshipNET)
- Perturbation analysis on the aforementioned data
- Technical notebook classes 

## Machine Learning and Adaptive Learning Module
This assignment is broken down into 2 parts. The first one looks at how to provide functional pipeline and tackle common real-world problems such as missing dat, splitting and pre-processing. The first part of part 1 looks into how to use Ridge Regression to predict air quality, given this [dataset](https://archive.ics.uci.edu/ml/datasets/Air+Quality), secondly we dive into a common ML algorithm : Random Forests to tackle the same problem. Technically, we look how to provide easy, reliable pipelines using common libraries such as Pandas and Sci-kit learn. 
The second part uses a blend of different [medical image datasets](https://medmnist.com) We look into the performance of different models on this dataset, from Multi-Layer Perceptron to Convolutional Neural Networks. We also analyse some unsupervised strateies to perform Dimensionality Reduction (PCA) and Clustering (Spectral Clustering), we also use AutoEncoders. From a technical point of view, this part perform model optimisation in PyTorch.



