# Forged Signature Detection

This project focuses on detecting forged signatures using machine learning and image processing techniques. The goal is to differentiate between genuine and forged signatures through a combination of preprocessing steps and a deep learning model.

## Project Overview

The approach involves:
1. **Data Preprocessing**: Images of signatures are processed through steps like grayscale conversion, thresholding, and noise reduction to prepare them for analysis.
2. **Feature Extraction**: Using image processing libraries, key features from the signatures are extracted for classification.
3. **Model Training**: A neural network model is trained using TensorFlow and Keras to classify signatures as either genuine or forged.
4. **Evaluation**: The model's performance is evaluated based on accuracy, precision, recall, and other metrics to ensure reliable detection.

## Dependencies

- Python 3.x
- TensorFlow (with v1 compatibility)
- Keras
- NumPy
- SciPy
- scikit-image
- Matplotlib

## Dataset

The dataset used in this project is split into two folders:
- `real/` - Contains genuine signature images.
- `forged/` - Contains forged signature images.

## Usage

1. Clone the repository and install the dependencies.
2. Place the dataset in the appropriate folders.
3. Run the Jupyter Notebook to train and evaluate the model.

## Results

The project demonstrates how deep learning and image processing techniques can effectively detect forged signatures with high accuracy.
