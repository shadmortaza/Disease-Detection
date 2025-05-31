# 🧠 AI Disease Detection

This project explores how artificial intelligence can support early diagnosis of diseases using both **tabular medical data** and **X-ray images**. The aim is to build decision-support tools, not replacements for medical professionals.

---

## 🔍 Project Overview

Datasets:
1. **Tabular data (Dataset1.csv):** Contains patient health records including age, BMI, smoking status, etc.
2. **X-ray images (Dataset 2):** Used for detecting pneumonia through image classification.

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
