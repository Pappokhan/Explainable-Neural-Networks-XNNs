# Explainable Neural Networks (XNNs) with Image Classification

This repository demonstrates the implementation of Explainable Neural Networks (XNNs) for image classification, focusing on enhancing model interpretability through advanced explanation techniques.

## Overview

This project implements a convolutional neural network (CNN) model with an attention mechanism, trained on the CIFAR-10 dataset. The model is designed to classify images while providing clear and interpretable explanations for its predictions. The project incorporates state-of-the-art explainability techniques such as Grad-CAM, LIME, and SHAP to visualize and understand the decision-making process of the model.

## Features

- **CNN with Attention Mechanism:** A convolutional neural network enhanced with attention layers to focus on the most relevant parts of the image.
- **Grad-CAM Visualization:** Generates heatmaps highlighting the regions of the image that most influenced the model's decision.
- **LIME Explanations:** Provides local explanations by identifying the most important superpixels contributing to the classification.
- **SHAP Explanations:** Utilizes SHAP's DeepExplainer to offer more detailed local explanations, showcasing the contribution of each pixel to the model's prediction.
- **Advanced Rule-Based Integration:** Includes a rule-based system to refine predictions by incorporating domain-specific knowledge, such as color features.

## Getting Started

### Prerequisites

- Python 3.x
- TensorFlow/Keras
- NumPy
- Matplotlib
- OpenCV
- PIL
- LIME
- SHAP

Install the required packages using pip:

```bash
pip install tensorflow numpy matplotlib opencv-python pillow lime shap
