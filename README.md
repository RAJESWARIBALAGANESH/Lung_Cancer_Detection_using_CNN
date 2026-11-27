# 🫁 Lung Cancer Detection Using Deep Learning | Custom CNN Model

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-FF6F00?logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![Keras](https://img.shields.io/badge/Keras-Deep%20Learning-D00000?logo=keras&logoColor=white)](https://keras.io/)
[![OpenCV](https://img.shields.io/badge/OpenCV-Image%20Processing-5C3EE8?logo=opencv&logoColor=white)](https://opencv.org/)
[![Google Colab](https://img.shields.io/badge/Google%20Colab-Notebook-F9AB00?logo=googlecolab&logoColor=white)](https://colab.research.google.com/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rajeswari%20Balaganesh-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rajeswari-balaganesh-/)

A deep learning-based **Lung Cancer Detection** model built with a custom Convolutional Neural Network (CNN) to classify lung CT scan images into three categories: **Benign**, **Malignant**, and **Normal**.

---

## 📋 Table of Contents
- [Project Overview](#-project-overview)
- [Problem Statement](#-problem-statement)
- [Dataset](#-dataset)
- [Technology Stack](#-technology-stack)
- [Implementation Workflow](#-implementation-workflow)
- [Model Results](#-model-results)
- [Getting Started](#-getting-started)
- [Key Learnings](#-key-learnings)
- [Potential Applications](#-potential-applications)
- [Connect With Me](#-connect-with-me)
- [Disclaimer](#-disclaimer)

---

## 💡 Project Overview

The model processes lung CT scan images and classifies them into three distinct diagnostic categories:

| Class | Description |
| :--- | :--- |
| 🟢 **Benign** | Abnormal tissue growth that is non-cancerous |
| 🔴 **Malignant** | Cancerous growths requiring medical intervention |
| 🔵 **Normal** | Healthy lung CT scans with no detected abnormalities |

---

## ⚠️ Problem Statement

Medical image analysis requires careful examination and specialized clinical expertise. This project explores the application of deep learning in automated medical image classification, supporting research into AI-assisted healthcare solutions and early screening workflows.

---

## 📂 Dataset

- **Dataset Name:** IQ-OTH/NCCD Lung Cancer Dataset
- **Classes:** `Benign cases`, `Malignant cases`, `Normal cases`
- **Preprocessing:** Images are resized to `64 × 64` pixels, normalized, and partitioned into training and validation sets using `split-folders`.

---

## 🛠️ Technology Stack

- **Programming Language:** Python
- **Deep Learning Framework:** TensorFlow, Keras (Custom CNN Architecture)
- **Image Processing & Numerics:** NumPy, OpenCV, Pillow (PIL)
- **Dataset Management:** `split-folders`
- **Development Environment:** Google Colab

---

## ⚙️ Implementation Workflow

```text
📂 Dataset Collection (IQ-OTH/NCCD Lung Cancer Dataset)
   │
   ▼
🖼️ Image Preprocessing & Resizing (64 × 64, Normalization, Train/Val Split)
   │
   ▼
🧠 Custom CNN Feature Extraction (Conv2D → MaxPooling2D → Dropout → Dense)
   │
   ▼
🔧 Model Training & Validation (3 Epochs)
   │
   ▼
📊 Performance Evaluation (Accuracy, Loss, Confusion Matrix, Classification Report)
   │
   ▼
🔍 Three-Class Classification & Unseen CT Scan Prediction

## 📊 Model Results & Evaluation

| Metric | Value / Outcome |
| :--- | :--- |
| **Validation Accuracy** | **94.11%** |
| **Validation Loss** | **~0.149** |
| **Classification Scope** | 3-Class (`Benign`, `Malignant`, `Normal`) |
| **Evaluation & Inference** | Confusion matrix, classification metrics, and single-image inference on unseen CT scans |

🎯 Key Learnings
Designing and building a custom Convolutional Neural Network (CNN) architecture from scratch.

Developing end-to-end image preprocessing, resizing (64 × 64), and normalization pipelines.

Structuring automated train/validation dataset splits using split-folders.

Evaluating multi-class medical image models using validation loss, accuracy, and confusion matrices.

Running inference on individual, previously unseen lung CT scan images.

🌍 Potential Applications
Medical image analysis and computer vision research.

Automated multi-class medical image classification pipelines.

AI-assisted clinical decision support and healthcare research.

🤝 Connect With Me
LinkedIn: Rajeswari Balaganesh https://www.linkedin.com/in/rajeswari-balaganesh-/

GitHub: @rajeswaribalaganesh03 (second account)

⚠️ Disclaimer
This is an experimental research and educational project. It is not a certified medical device and is not intended to replace professional medical diagnosis, clinical judgment, or treatment.
