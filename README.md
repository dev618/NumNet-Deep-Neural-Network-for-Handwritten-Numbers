# 🧠 NumNet – Deep Neural Network for Handwritten Numbers

This project demonstrates how to build and train a simple neural network to recognize handwritten digits from the MNIST dataset using **TensorFlow** and **Keras**.

---

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep%20Learning-orange?logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-Neural%20Networks-red?logo=keras)
![NumPy](https://img.shields.io/badge/NumPy-Array%20Processing-blue?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Data%20Visualization-yellow?logo=matplotlib)
![MNIST](https://img.shields.io/badge/MNIST-Digit%20Dataset-green)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-Model-orange)

---

**Tags:**  
[`deep-learning`](#) [`neural-networks`](#) [`tensorflow`](#) [`keras`](#) [`mnist`](#) [`digit-recognition`](#) [`image-classification`](#) [`handwritten-digits`](#) [`machine-learning`](#) [`python`](#) [`numpy`](#) [`matplotlib`](#) [`classification-model`](#) [`ai-project`](#) [`pattern-recognition`](#) [`computer-vision`](#) [`feedforward-network`](#) [`supervised-learning`](#) [`data-preprocessing`](#) [`end-to-end-project`](#) [`portfolio-project`](#)

---

## 🗂️ Overview

The MNIST dataset is a classic benchmark in the field of machine learning. It contains:
- **60,000** training images
- **10,000** test images  
Each image represents a **grayscale handwritten digit (0–9)** in a **28x28 pixel** format.

This project builds a **basic feedforward neural network** to classify these digits with high accuracy using deep learning techniques.

---

## ⚙️ Key Features

✅ Loads and preprocesses the MNIST dataset  
✅ Builds a sequential neural network model with:
- Input layer (flattened 28x28 image)
- Hidden dense layer with 128 neurons and **ReLU** activation
- Output layer with 10 neurons and **softmax** activation

✅ Trains the model using a validation split  
✅ Evaluates the model on test data  
✅ Visualizes predictions on sample test images

---

## 🏁 Results

After training the model for **10 epochs**, it achieves the following:

- **Training Accuracy**: ~99.8%  
- **Validation Accuracy**: ~97.6%  
- **Test Accuracy**: ~97.7%

---

## 🚀 How to Use

### 1️⃣ Install Required Packages
```bash
pip install tensorflow matplotlib numpy

Run the Script
python num_net.py
