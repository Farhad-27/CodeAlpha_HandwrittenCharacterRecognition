# Handwritten Character Recognition using CNN

## Project Overview

This project focuses on recognizing handwritten digits (0–9) using a Convolutional Neural Network (CNN). The model is trained on the MNIST dataset to accurately classify handwritten digit images into their corresponding numerical classes.

This project is completed as part of the **CodeAlpha Machine Learning Internship – Task 3: Handwritten Character Recognition**.

## Objectives

- Build a CNN-based handwritten digit recognition model.
- Train and evaluate the model using the MNIST dataset.
- Analyze model performance using standard evaluation metrics.
- Visualize training performance and prediction results.

## Dataset

**Dataset:** MNIST Handwritten Digits Dataset

- Training Images: 60,000
- Testing Images: 10,000
- Image Dimensions: 28 × 28 pixels
- Number of Classes: 10 (Digits 0–9)
- Image Format: Grayscale

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Model Architecture

A Convolutional Neural Network (CNN) is used for handwritten digit classification.

The model includes:

- Convolutional Layers
- ReLU Activation
- Max Pooling Layers
- Flatten Layer
- Fully Connected (Dense) Layers
- Softmax Output Layer

## Project Workflow

1. Load the MNIST dataset.
2. Preprocess and normalize image data.
3. Build the CNN architecture.
4. Train the model.
5. Evaluate performance on test data.
6. Generate classification metrics and visualizations.

## Repository Contents

| File | Description |
|---|---|
| `CodeAlpha_HandwrittenCharacterRecognition.ipynb` | Complete project source code |
| `best_mnist_cnn.keras` | Trained CNN model |
| `test_metrics.csv` | Test evaluation metrics |
| `classification_report.txt` | Classification performance report |
| `training_curves.png` | Training and validation curves |
| `confusion_matrix.png` | Confusion matrix visualization |
| `sample_predictions.png` | Sample model predictions |
| `run_summary.json` | Training and evaluation summary |

## Results

The trained CNN model is evaluated using:

- Test Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

Refer to the evaluation files in this repository for detailed performance results.

## How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/YOUR_USERNAME/CodeAlpha_HandwrittenCharacterRecognition.git
   ```

2. Open the `.ipynb` file using Google Colab or Jupyter Notebook.

3. Run the notebook cells sequentially.

## Internship

**Organization:** CodeAlpha  
**Domain:** Machine Learning  
**Task:** Task 3 – Handwritten Character Recognition

---

**Author:** Farhad Hossain Fahim
