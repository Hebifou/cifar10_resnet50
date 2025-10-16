# CIFAR-10 – ResNet50 Image Classification Benchmark (Public Version)

This project presents a **deep learning benchmark** on the classic **CIFAR-10 dataset**, comparing training performance and model accuracy using **ResNet50**.  
The goal is to demonstrate efficient **CNN training workflows** and **evaluation techniques** for small image datasets.

---

## Project Overview

- **Objective:** Train and evaluate a convolutional neural network (ResNet50) on the CIFAR-10 dataset.  
- **Focus:** Model performance, training stability, and interpretability of classification results.  
- **Key Learning Goals:**
  - Efficient GPU training on image datasets
  - Tracking and visualizing loss & accuracy over epochs
  - Confusion matrix and error analysis

---

## Methods & Tools

| Category | Details |
|-----------|----------|
| **Model** | ResNet50 (PyTorch `torchvision.models`) |
| **Dataset** | CIFAR-10 (10 classes, 32×32 color images) |
| **Frameworks** | PyTorch, Torchvision, scikit-learn, Matplotlib |
| **Hardware** | GPU-enabled Colab runtime (recommended) |

---

## Key Visualizations

| Visualization | Description |
|----------------|-------------|
| **Learning Curves** | Training vs. validation loss and accuracy per epoch |
| **Confusion Matrix** | Model performance across all 10 CIFAR-10 classes |
| **Sample Predictions (optional)** | Qualitative examples of correctly and incorrectly classified images |

<p align="center">
  <img src="reports/figures/resnet50_learning_curves.png" width="48%" />
  <img src="reports/figures/resnet50_confusion_matrix.png" width="48%" />
</p>

---
