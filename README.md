# MNIST Handwritten Digit Classification using TensorFlow & Keras

## Project Overview
This project focuses on building a deep learning model to classify handwritten digits (0–9) using the MNIST dataset. The goal is to understand neural network fundamentals, model training, evaluation, and hyperparameter tuning.

---

## Dataset Information
- Dataset: MNIST Handwritten Digits  
- Training Samples: 60,000  
- Testing Samples: 10,000  
- Image Size: 28x28 pixels (grayscale)  
- Classes: 10 (digits 0–9)

---

## Model Architecture
- Input Layer: Flatten (28x28 → 784)  
- Hidden Layers:
  - Dense (128, ReLU)
  - Dense (128, ReLU)
- Output Layer:
  - Dense (10, Softmax)

Optimizer: Adam  
Loss: Sparse Categorical Crossentropy  
Metric: Accuracy  

---

## Experiments
Different configurations tested:
- Learning rates: 0.01, 0.001, 0.0005  
- Epochs: 10–30  
- Architectures: Multiple hidden layer variations  

---

## Results
Achieved ~97–98% accuracy on test dataset.

---

## Key Learnings
- Importance of normalization  
- Effect of hyperparameters  
- Overfitting vs underfitting  
- Neural network tuning  

---

## Technologies Used
Python, TensorFlow, Keras, NumPy, Matplotlib, Seaborn  

---
