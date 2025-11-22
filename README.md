# Python_Classification_CNN-EfficientNet-B0
This repository contains an experimental deep learning workflow for scene classification using a Convolutional Neural Network (CNN) for classificate paddy leaf dieses. The project explores the impact of data augmentation, hyperparameter autotuning, and k-fold cross-validation on model performance. This is 2023 Project

The training was conducted using RMSProp optimizer with a learning rate of 0.001, and the final model was trained for approximately 40–30 epochs based on autotuned settings.

implements a complete training pipeline for scene classification, focusing on:
* Normal dataset + augmented dataset
* Autotuned hyperparameters
* RMSProp optimizer (lr = 0.001)
* 40–30 epoch training cycles
* 5-fold cross-validation for model evaluation

Model Architecture & Training Setup
* Model Type: Convolutional Neural Network (CNN) EfficientNet-B0
* Optimizer: RMSProp
* Learning Rate: 0.001
* Epochs: ~40 epochs (autotuned)
* Loss Function: Categorical Crossentropy
* Augmentation: Random flips, rotations, zooms, etc.
* Autotuning: Automated search for optimal hyperparameters
* Cross-Validation: 5-fold

Training Accuracy
* 98%. the model performs extremely well on the training set, indicating that the architecture and augmentation pipeline are effective in learning the patterns.
5-Fold Cross-Validation Accuracy
*  71% (average). This result shows a significant performance drop compared to the training accuracy, which suggests:
