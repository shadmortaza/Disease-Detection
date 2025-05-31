# 🧠 AI Disease Detection

This project explores how artificial intelligence can support early diagnosis of diseases using both **tabular medical data** and **X-ray images**. The aim is to build decision-support tools, not replacements for medical professionals.

---

## 🔍 Project Overview

Datasets:
1. **Tabular data :** Contains patient health records including age, BMI, smoking status, etc.
2. **X-ray images :** Used for detecting pneumonia through image classification.

Our models include:
- Binary & multi-class classification (tabular)
- Convolutional Neural Networks (X-ray)
- Variational Autoencoders for image denoising

---

## 📁 Repository Structure

data/

├── Patientdata.csv # Tabular patient data

├── Patientinfo.xlsx # Patient data info

└── Load_Xrayimages.ipynb # Load and explore X-ray dataset

notebooks/

├── Multiclassclassification.ipynb

├── CNN.ipynb

└── VAE.ipynb

---

## 🧪 Models & Tasks

### Tabular Data (Dataset 1)
- Binary classification (diabetes, stroke, heart disease)
- Multi-class classification for multiple disease detection
- Feature selection for performance optimisation

### X-ray Images (Dataset 2)
- CNN-based pneumonia classifier
- Variational Autoencoder (VAE) for image denoising

---

## 📊 Evaluation

- **Classification models:** Confusion matrix, precision, recall, F1-score
- **Generative model (VAE):** RMSE and relative RMSE for reconstruction quality

---

## 🔧 Tools Used

- Python, pandas, NumPy
- scikit-learn
- TensorFlow / Keras
- Matplotlib, Seaborn
- Jupyter Notebooks
- Google Colab

## 💡 Purpose

This project was developed to explore how artificial intelligence techniques can support early disease detection using both structured (tabular) and unstructured (image) data. It aims to apply multiple ML approaches—classical classification models, CNNs, and VAEs—to real-world healthcare scenarios, with a focus on practical implementation, model evaluation, and data-driven insights.

Key AI skills I was able to learn during this project:
- Data preprocessing and feature selection
- Supervised learning (binary and multi-class classification)
- Deep learning for image classification
- Generative models for image reconstruction
- Model performance evaluation and interpretation

Ultimately, this project showcases how data and AI can work together to support medical decision-making in a responsible, explainable, and meaningful way.

