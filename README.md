# 🌿 Plant Disease Detection Using CNN + Streamlit  
**Author:** Praveen Kumar
---

## 🔍 Project Overview

This project builds a **Convolutional Neural Network (CNN)** that accurately classifies plant diseases based on leaf images. It further integrates the model into a **Streamlit web application** that allows users to upload an image and get instant predictions.

With over 38 plant disease categories, this system provides a practical solution to aid farmers and researchers in diagnosing plant diseases early, promoting **sustainable agriculture**.

---

## 🎯 Problem Statement

> Design and deploy an image classification model that can detect a variety of plant diseases across multiple crops with high accuracy using computer vision.

---

## 🌱 Dataset

- **Type:** Plant Village Dataset (multi-class image dataset)  
- **Classes:** 38 different categories (e.g. Tomato Leaf Mold, Apple Scab, Corn Rust, etc.)  
- **Labels:** Healthy vs diseased (crop-specific)  
- **Images:** Preprocessed to `224x224` resolution
- **Dataset:** https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset

---

## 🧠 Model Architecture

- **Framework:** TensorFlow / Keras  
- **Model:** Custom CNN  
  - Conv2D → MaxPooling → Dropout → Flatten → Dense  
- **Activation:** ReLU, Softmax  
- **Loss Function:** Categorical Crossentropy  
- **Optimizer:** Adam  
- **Input Shape:** `(224, 224, 3)`
- **Model:** https://drive.google.com/file/d/1gTUllvoZMRP4HBXMK7TBv2YhqZHXVjyl/view?usp=share_link

---

## 🧪 Evaluation Metrics
