# Chest X-Ray Image Classification Using Deep Learning

This repository contains the final project for the Deep Learning course at Bar-Ilan University, which focuses on classifying chest X-ray images into categories: healthy, viral pneumonia, or bacterial pneumonia using deep learning techniques.

## Project Overview

The project uses deep learning models to classify chest X-ray images:

- **Binary Classification Model**: Distinguishes between healthy and pneumonia cases.
- **Categorical Classification Model**: Classifies images into healthy, bacterial pneumonia, and viral pneumonia.
- **Autoencoder for Anomaly Detection**: Identifies anomalies by reconstructing normal images and detecting deviations.
- **Model Explainability**: Uses Heat Maps by Occlusion and Grad-CAM to visualize and interpret the decisions made by the models.

## Repository Contents

- [`train.ipynb`](train.ipynb): This Jupyter notebook includes all preprocessing, modeling, training, and evaluation code along with detailed explanations.
- [`report.pdf`](report.pdf): Contains a comprehensive report detailing the methodologies, experiments, and findings of the project, structured as a scientific paper.

## Using the Notebook

To use the notebook, simply make a copy of it in Google Colab:

1. Open the notebook in Google Colab: [train.ipynb](https://colab.research.google.com/drive/1PnqX2i2yCM7GaSn1WeUKzlsVsk9dwD8v)
2. Make a copy of it to your drive by clicking `File` -> `Save a copy in Drive...` 

This will allow you to run and modify the notebook as needed.

## Report

The `report.pdf` provides a detailed account of the project including the problem statement, deep learning techniques employed, results of the experiments conducted, and conclusions drawn from the findings. It serves as a full written documentation of the project workflow and outcomes.

## Authors

- **Asaf Mesilaty** - [GitHub Profile](https://github.com/AsafMesi)

## Acknowledgments

- Dataset source: [Kaggle Chest X-ray Pneumonia](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)
- Inspiration for Grad-CAM: [Keras Documentation](https://keras.io/examples/vision/grad_cam/)
