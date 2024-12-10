# Accelerating MRI Reconstruction Using Deep Learning

## Overview
This project focuses on accelerating MRI reconstruction using deep learning methods while maintaining diagnostic quality. We leverage U-Net and ResNet architectures and incorporate domain-specific physics constraints to address the limitations of traditional reconstruction techniques.

The project is part of **CS 7643 - Deep Learning (Fall 2023)** and was developed as a group effort to explore the potential of deep learning in medical imaging.

## Features
- **U-Net Architecture**: A modified U-Net for MRI reconstruction, emphasizing diagnostically significant regions using weighted loss functions.
- **ResNet Exploration**: Comparison of U-Net with ResNet-based models for improved performance.
- **Physics-Based Constraints**: Integration of domain-specific MRI principles for better reconstruction consistency.
- **Grad-CAM Visualization**: Interpretability through Grad-CAM overlays to highlight regions of diagnostic importance.

## Datasets
The project utilized the following datasets:
1. **[fastMRI Dataset](https://fastmri.med.nyu.edu/)**: Fully sampled and under-sampled k-space data for training and validation.
2. **[KneeMRI Dataset](https://www.kaggle.com/datasets/sohaibanwaar1203/kneemridataset)**: for validation of region of interest.

## Team Members
* Fidel Morales
* Minuk Lee
* Kyaw Htoon