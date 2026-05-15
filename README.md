# NN_Project
# MNIST Handwritten Digit Recognition using MLP

## Problem Description

This project implements a Multilayer Perceptron (MLP) neural network using PyTorch for handwritten digit recognition on the MNIST dataset.

The model classifies grayscale handwritten digit images into one of 10 classes (0–9).

Two experiments were performed using different:
- Activation functions
- Hidden layer sizes
- Regularization techniques

The project also includes:
- Training and testing evaluation
- Accuracy and loss monitoring
- Visualization of training performance

---

## Dataset 

Dataset: MNIST Handwritten Digits Dataset


---

## Model Architecture

### Experiment 1
- Activation Function: ReLU
- Hidden Layers:
  - 128 neurons
  - 64 neurons
- Optimizer: Adam
- Learning Rate: 0.001

### Experiment 2
- Activation Function: Tanh
- Hidden Layers:
  - 256 neurons
  - 128 neurons
- Dropout: 0.3
- Optimizer: Adam
- Learning Rate: 0.001

---

## Results



| Experiment 1 | ReLU | 128 → 64 | 0.9770 |
| Experiment 2 | Tanh + Dropout | 256 → 128 | 0.9763 |

---

## Visualizations

The project includes:
- Training Loss Curves
- Accuracy Curves

These visualizations help monitor model learning and compare experiments.

---

## Libraries Used

- PyTorch
- Torchvision
- Matplotlib

---

## Instructions for Running the Project

### 1. Install Dependencies


pip install torch torchvision matplotlib
