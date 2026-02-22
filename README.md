# Graduate Admission Prediction – Keras

Regression model built using Keras to predict graduate admission probability based on academic profile features.

---

## 📌 Overview

This project is a learning-based implementation of a machine learning model using Keras (TensorFlow) to predict the **Chance of Admission** for graduate studies based on academic and profile parameters.

The main goal of this project was to:

- Understand how Keras works
- Learn how neural networks are built and trained
- Understand loss functions and evaluation metrics
- Practice model training, validation, and performance visualization

This is a **regression problem**, not a classification task.

---

## 📊 Dataset

The dataset contains the following features:

- GRE Score  
- TOEFL Score  
- University Rating  
- SOP Strength  
- LOR Strength  
- CGPA  
- Research Experience  
- Chance of Admit (Target Variable)

Target variable:

**Chance of Admit → Continuous value between 0 and 1**

---

## 🧠 Problem Type

- ✔ Regression  
- ❌ Not Classification  

Since the output is a continuous probability value, regression metrics are used.

---

## ⚙️ Model Architecture

- Input Layer  
- Hidden Dense Layers (ReLU activation)  
- Output Layer (Linear activation)  

**Loss Function:** Mean Squared Error (MSE)  
**Evaluation Metric:** Mean Absolute Error (MAE)

---

## 📈 Training Details

- Optimizer: Adam  
- Validation Split: 20%  

Performance tracked:

- Training Loss  
- Validation Loss  
- Training MAE  
- Validation MAE  

---

## 🧪 Key Learnings

- Difference between Classification and Regression  
- Proper metric selection  
- Model compilation in Keras  
- Plotting training vs validation performance  
- Importance of choosing correct output activation  

---i 

## 📚 Tech Stack

- Python  
- TensorFlow / Keras  
- NumPy  
- Pandas  
- Matplotlib  

---

## 🎯 Purpose of This Repository

This repository is a learning milestone project created to build foundational understanding of deep learning with Keras.

It is not intended as a production-ready system, but as a step in the learning journey toward applied machine learning.
