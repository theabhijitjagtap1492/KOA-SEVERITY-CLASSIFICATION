# KOA-SEVERITY-CLASSIFICATION

# 🦴 Knee Osteoarthritis Severity Classification

This repository contains the final project for the **Complex Data Mining** course at **Savitribai Phule Pune University (SPPU)**.

---

## 📌 Project Overview

Knee osteoarthritis (OA) is a degenerative joint disease caused by the gradual wearing of cartilage. X-ray and MRI imaging are commonly used to assess the loss of joint space and determine the severity of the disease.

This project leverages deep convolutional neural networks (CNNs) to automatically classify the severity of knee osteoarthritis from X-ray images.

---

## 🩻 Osteoarthritis Severity - KL Score

The **Kellgren and Lawrence (KL)** grading system is used to assess OA severity in five levels:

| Grade | Description |
|-------|-------------|
| 0     | Healthy     |
| 1     | Doubtful    |
| 2     | Minimal     |
| 3     | Moderate    |
| 4     | Severe      |

> 📸 The dataset used in this project includes labeled X-ray images corresponding to these grades.

---

## 🚀 Features

- ✅ Deep learning-based classification using CNN architectures
- ✅ Ensemble models using accuracy- and F1-score-based weighting
- ✅ Visualization of confusion matrices for performance insight
- ✅ Streamlit-based web app for interactive inference
- ✅ Easy image-based inference via CLI

---

## 🗂️ Directory Structure

knee-osteoarthritis-analysis/
├── app.py
├── archive.zip
├── requirements.txt
├── assets/
│   ├── confusion_matrix_3_ensemble.png
│   ├── data.png
│   ├── Doubtful.png
│   ├── ensemble_best.png
│   ├── ensemble.png
│   ├── Healthy.png
│   ├── KL-score.png
│   ├── Minimal.png
│   ├── Moderate.png
│   ├── Severe.png
│   ├── streamlit_knee_logo.png
│   └── streamlit_knee_ss.png
├── app/
│   └── img/
│       └── NG1.jpg
├── models/
│   ├── model_ResNet50_ft.hdf5
│   ├── model_Xception_ft.hdf5
│   └── model_Inception_ResNet_V2_ft.hdf5
├── dataset/
│   ├── train/
│   ├── val/
│   └── test/
├── notebooks/
│   ├── 01_data_preparation.ipynb
│   ├── 02_ensemble_models.ipynb
│   ├── 03_best_model_on_test_xception.ipynb
│   ├── 02_model_inception.ipynb
│   ├── 02_model_resnet50.ipynb
│   ├── 02_model_xception.ipynb
│   └── 03_evaluate_model.ipynb


