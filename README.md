# Gastrointestinal Disease Diagnosis using Deep Learning

This repository contains the code and research paper for a deep learning framework designed for **gastrointestinal disease classification** from endoscopic images. The project integrates **image enhancement techniques** and **multi-task learning** (classification + segmentation) to improve diagnostic performance.


## Repository Contents

- `GastroIntestinal.pdf` – The full research paper detailing the methodology, experiments, results, and analysis.
- `Code.ipynb` – Jupyter Notebook containing the code implementation. The notebook includes:
  - Data preprocessing and image enhancement
  - Model training using EfficientNet and U-Net inspired architectures
  - Evaluation of classification and segmentation performance
  - Visualization of Grad-CAM results and predictions
  - Test set performance metrics


## Features

- **Advanced Image Enhancement**: Contrast enhancement, noise removal, gamma correction, and edge fusion.
- **Deep Learning Models**: EfficientNet for classification and a U-Net-inspired decoder for auxiliary segmentation learning.
- **Multi-Task Learning**: Joint optimization of classification and segmentation improves lesion localization and overall accuracy.
- **Visualization**: Grad-CAM visualizations for interpretability and analysis of model predictions.
- **Dataset**: Experiments are performed on the **Kvasir gastrointestinal image dataset**.
