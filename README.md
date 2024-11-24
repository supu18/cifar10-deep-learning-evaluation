# CIFAR-10 Deep Learning Evaluation

This repository contains implementations of convolutional neural networks (CNNs) for evaluating image classification performance on the CIFAR-10 dataset. It includes a basic CNN model (`SimpleCNN`) and a deeper architecture using DenseNet. Additionally, a ready-to-use Google Colab notebook is provided for easy experimentation.

## Features
- **Dataset**: CIFAR-10, a standard benchmark dataset for image classification tasks.
- **Models**:
  - `SimpleCNN`: A lightweight architecture suitable for quick experimentation.
  - `DenseNet`: A deeper architecture for improved performance and generalization.
- **Google Colab Notebook**: Interactive notebook for training and evaluation.
- **Training & Evaluation Pipeline**: Modularized training and testing code.
- **Metrics**: Reports training loss and test accuracy.

## Requirements
To replicate the experiments locally, ensure you have the following:
- Python 3.8 or later
- PyTorch 1.11 or later
- torchvision 0.12 or later
- Other dependencies (install via `pip install -r requirements.txt`):
  - numpy

Alternatively, you can use the provided Google Colab notebook for a cloud-based, dependency-free environment.

## Installation
1. Clone the repository:
   ```bash
   git clone <link>
   cd cifar10-deep-learning-evaluation
