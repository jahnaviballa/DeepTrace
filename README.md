# 🔍 DeepTrace: Multi-Modal Deepfake Detection

**Deepfake detection using ResNeXt+LSTM for video, CNN for audio, and DenseNet121 with Grad-CAM for images – all in Jupyter notebooks.**

![DeepTrace](https://img.shields.io/badge/Deepfake%20Detection-AI%20Powered-brightgreen)
![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange.svg)

---

## 🧠 Project Overview

**DeepTrace** is a comprehensive deepfake detection system built with deep learning techniques across **three modalities**:

- 🎞️ **Video**: ResNeXt50 + LSTM architecture to analyze facial movement and temporal consistency
- 🎧 **Audio**: CNN model to classify real vs. synthetic voices
- 🖼️ **Images**: DenseNet121 with Grad-CAM to localize and detect manipulation patterns

> All models are trained and tested in Kaggle notebooks using well-curated datasets.

---

## 🧩 Key Features

- ✅ Detects deepfakes from **video**, **audio**, and **image** inputs
- 📈 **Grad-CAM** visual explanations for image classification
- 🎥 **Face extraction pipeline** for clean video preprocessing
- 📊 Model evaluations: **accuracy**, **ROC curves**, **confusion matrices**
- 💾 Model files: `.pt` for PyTorch, `.h5` for Keras/TensorFlow
- 📁 Modular notebooks for each modality




