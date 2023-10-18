# Optdigits-Dimension-Reduction-and-Classification

This repository contains Python implementations for applying dimension reduction and classification techniques on the Optdigits dataset.

Problem Statement
In this project, we implement k-Nearest Neighbor (KNN) classification without Principal Component Analysis (PCA) and with PCA. We visualize the dataset in a 2D space using PCA and KNN, aiming to optimize classification performance.

optdigits_train.txt: Training data file for the Optdigits dataset.
optdigits_test.txt: Test data file for the Optdigits dataset.

Contains the implementation of the KNNClassifier class for KNN classification. The class employs the k-Nearest Neighbor algorithm using Euclidean distance metric.
Contains the implementation of the PCA class for Principal Component Analysis. This class computes PCA using eigen decomposition on the input data.
Implements KNN classification without PCA and with PCA. It also includes visualization of the dataset in 2D space using PCA and KNN.

Results:

Error rates for different values of k will be displayed when running KNN with and without PCA.
2D plots representing the dataset in the projected space will be saved as training_data_pca.png and test_data_pca.png.
