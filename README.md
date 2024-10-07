# COPD Classification Using CNN

This repository contains the implementation of a Convolutional Neural Network (CNN) for the classification of Chronic Obstructive Pulmonary Disease (COPD) based on medical imaging (e.g., X-rays, CT scans, or lung function data). The goal of this project is to develop a deep learning model that can assist in the early detection and classification of COPD using state-of-the-art CNN architectures.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Installation](#installation)

## Introduction

Chronic Obstructive Pulmonary Disease (COPD) is a progressive lung disease characterized by obstructed airflow, which can lead to difficulty breathing. Early detection is critical for managing COPD and improving patient outcomes. This project leverages deep learning, specifically a Convolutional Neural Network (CNN), to classify medical images as either normal or indicative of COPD.

The project explores various CNN architectures and fine-tunes hyperparameters to achieve the highest accuracy in detecting COPD from medical imaging.

## Dataset

The dataset used for this project provided by Professor Kyle Hasenstab (Assistant Professor Department of Mathematics and Statistics at San Diego State University). The dataset consists of medical images labeled as either:
- **Normal**: Healthy individuals without COPD.
- **COPD**: Patients diagnosed with COPD at different stages.

## Model Architecture

The model is built using a CNN to automatically learn features from the medical images. The architecture consists of the following layers:
- **Convolutional Layers**: To extract spatial features from the images.
- **Pooling Layers**: To reduce the spatial dimensions of the features.
- **Fully Connected Layers**: For classification, including dropout to prevent overfitting.
- **Softmax Layer**: To output probabilities for each class (normal vs. COPD).


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/COPD-Classification-CNN.git
   cd COPD-Classification-CNN
   ```
