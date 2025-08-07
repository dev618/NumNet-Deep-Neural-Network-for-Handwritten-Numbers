# 🧠 Handwritten Digit Recognition using Neural Networks

This project demonstrates how to build and train a simple neural network to recognize handwritten digits from the MNIST dataset using **TensorFlow** and **Keras**.

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
