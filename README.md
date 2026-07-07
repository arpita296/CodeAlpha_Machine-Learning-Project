# CodeAlpha_Machine-Learning-Project

# TASK 1- Project Title
  Credit Scoring Model using Machine Learning
  

# Objective
  Predict an individual's creditworthiness using past financial data.

# Algorithms Used
1.Logistic Regression

2.Decision Tree

3.Random Forest

# Dataset
  Give Me Some Credit (Kaggle)

# Evaluation Metrics
  Accuracy
  Precision
  Recall
  F1-Score
  ROC-AUC
# Best Model
  Three classification algorithms—Logistic Regression, Decision Tree, and Random Forest—were trained and evaluated. Based on the evaluation metrics, Random Forest achieved the best overall performance and was selected as the final model for predicting customer creditworthiness.

  # TASK2
  # Handwritten Character Recognition using CNN

# Project Overview

This project implements a **Handwritten Character Recognition** system using a **Convolutional Neural Network (CNN)**. The model is trained on the **MNIST** dataset to recognize handwritten digits from **0 to 9**.

The objective is to classify grayscale images of handwritten digits with high accuracy using deep learning techniques.




## Dataset

**Dataset:** MNIST Handwritten Digits Dataset

The dataset contains:

* 70,000 grayscale handwritten digit images
* Image size: **28 × 28 pixels**
* 60,000 training images
* 10,000 testing images
* 10 classes (Digits 0–9)

The dataset is loaded directly from TensorFlow:

```python
from tensorflow.keras.datasets import mnist
```

---

## Project Workflow

1. Import required libraries.
2. Load the MNIST dataset.
3. Explore the dataset (EDA).
4. Normalize image pixel values.
5. Reshape images for CNN input.
6. Build a Convolutional Neural Network.
7. Compile the model.
8. Train the model.
9. Evaluate model performance.
10. Predict handwritten digits.
11. Visualize predictions and performance metrics.
12. Save the trained model.

---

##  CNN Model Architecture

The model consists of:

* Conv2D Layer (32 filters, 3×3, ReLU)
* MaxPooling2D Layer
* Conv2D Layer (64 filters, 3×3, ReLU)
* MaxPooling2D Layer
* Flatten Layer
* Dense Layer (128 neurons, ReLU)
* Output Layer (10 neurons, Softmax)

---

##  Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

##  Model Evaluation

The trained model was evaluated on the MNIST test dataset using:

* Test Accuracy
* Test Loss
* Confusion Matrix
* Classification Report
* Sample Predictions

### Visualizations

The project includes:

* Sample handwritten digit images
* Training Accuracy Curve
* Validation Accuracy Curve
* Training Loss Curve
* Validation Loss Curve
* Confusion Matrix
* Sample Predictions

---


##  Results

The CNN model successfully learned to recognize handwritten digits with **high accuracy (approximately 98–99%)** on the MNIST test dataset.

The model demonstrates strong performance in classifying handwritten digits while maintaining a low test loss.

---

