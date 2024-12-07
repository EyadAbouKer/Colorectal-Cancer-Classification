# Transfer Learning & Image Classification Using CNNs

## Project Description

This project focuses on addressing image classification problems in real-world applications using Convolutional Neural Networks (CNNs). It encompasses two primary tasks:

1. Training CNN models to classify images in a dataset related to colorectal cancer.
2. Analyzing and visualizing feature extraction capabilities of pre-trained CNN models when applied to datasets related to prostate cancer and animal face classification.

## Key Features

- Use of state-of-the-art CNN architectures such as ResNet, VGG, AlexNet, MobileNet, or ShuffleNet.
- Implementation of t-SNE for dimensionality reduction and visualization.
- Transfer learning and knowledge sharing between datasets.
- Application of classical machine learning methods to classify extracted features.

## Datasets

1. **Colorectal Cancer Classification**: Reduced dataset of 6K image patches with 3 classes (smooth muscle, normal colon mucosa, cancer-associated stroma).
2. **Prostate Cancer Classification**: Reduced dataset of 6K image patches with 3 classes (tumor tissue, benign glandular tissue, benign non-glandular tissue).
3. **Animal Faces Classification**: Reduced dataset of 6K images with 3 classes (cats, dogs, wildlife).

## Repository Structure

```plaintext
src/            # Contains all source code
  train.py      # Code for training the CNN model
  analyze.py    # Code for analyzing and visualizing extracted features
notebooks/      # Jupyter notebooks for exploration and prototyping
data/           # Instructions for obtaining datasets (datasets not included due to size limitations)
results/        # Contains visualizations and results
models/         # Trained CNN models
README.md       # Project documentation
```

## Results
- Training accuracy/loss curves.
- t-SNE visualizations of feature embeddings.
- Classification accuracy metrics for each dataset.


## Project Team
- Mhd Eyad
- Hisham
- Omar
- Nour
- Nusrath
