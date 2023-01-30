# FixMatch
FixMatch is a semi-supervised deep learning algorithm for image classification tasks. This repository provides a Python implementation of the FixMatch algorithm. This repository is a Python implementation of the Semi-supervised FixMatch algorithm using Tensorflow. The implementation uses the CIFAR10 dataset and includes the following steps:

# Notebook description

 1. Data Loading: Import and normalize the CIFAR10 dataset and split the training set into labeled and unlabeled data.
 2. Supervised learning (baseline): Train a standard Convolutional Neural Network on the labeled data and evaluate its performance on the test set.
 3. FixMatch: Perform the FixMatch algorithm on the unlabeled data and evaluate its performance on the test set.

# Requirements

 - Tensorflow
 - Numpy
 - Keras

# Usage

To run the code, simply run the FixMatch.ipynb Jupyter notebook.

# Results
The results of the baseline and FixMatch algorithms are shown in the notebook and compared. The FixMatch algorithm can significantly improve the accuracy on the test set.

# Credits
This implementation is based on the paper "FixMatch: Simplifying Semi-Supervised Learning with Consistency and Confidence" by Soeren Pirk et al. (https://arxiv.org/abs/2001.07685)
