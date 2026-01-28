CNN and Neural Network Models



Overview

This repository contains the implementation of the work that focuses on building, training, optimizing, and evaluating neural networks and convolutional neural networks using PyTorch. All models are implemented from scratch without using pretrained architectures.



The work is structured into multiple parts covering fully connected neural networks, CNNs, VGG-style architectures, and a bonus ResNet-style model.



Project goal: Building Neural Networks and CNNs



Repository Structure

Data analysis and implementation of a basic fully connected neural network

Hyperparameter tuning and optimization of the neural network

Convolutional Neural Network (CNN) implementation and performance improvements

VGG-style CNN architecture adapted to the dataset

ResNet-style architecture implementation





Dataset

The CNN dataset is provided as part of the course assignment.

It contains 36 image classes with 2,800 samples per class (100,800 total images).

Each image is 28×28 pixels and may be grayscale or RGB.

The dataset is not included in this repository in accordance with course submission guidelines.



Methodology

Part I focuses on exploratory data analysis, preprocessing, and training a basic fully connected neural network.

Part II improves the neural network using systematic hyperparameter tuning and optimization techniques.

Part III implements a CNN architecture and applies multiple performance-enhancing methods.

Part IV implements a VGG-style CNN architecture adapted to smaller input dimensions.

The bonus section explores deeper architectures through a ResNet-style model.



Evaluation

Models are evaluated using accuracy, precision, recall, F1-score, confusion matrices, and ROC curves.

Training, validation, and test loss and accuracy trends are analyzed to assess convergence and generalization.

Saved model weights allow reproducibility without retraining.



How to Run

Install dependencies listed in requirements.txt.

Run notebooks sequentially from Part 1 through Part 4.

Run the bonus notebook separately if evaluating the ResNet implementation.

Saved weights can be loaded to reproduce results.



Notes

No pretrained or built-in CNN architectures were used, in accordance with assignment rules.

Large files such as datasets and model weights exceeding size limits are stored externally as required.

This repository is intended for academic demonstration purposes.



Authors

Harsha Venkateshwara

