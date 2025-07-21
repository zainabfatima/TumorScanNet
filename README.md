# 🧠 TumorScanNet: Brain Tumor Detection using Transfer Learning

This project applies **transfer learning** with pre-trained deep learning models (e.g., **VGG16**) to detect brain tumors from MRI images. It uses convolutional neural networks (CNNs) to classify brain scans into tumor and non-tumor categories.

---

## 📌 Features

- 🧪 Binary classification: Tumor vs. No Tumor
- 🧠 Utilizes **VGG16** architecture with transfer learning
- 📊 Accuracy, loss, and classification reports visualized
- 📁 Works with datasets containing MRI brain scan images
- 📈 Evaluation using confusion matrix, accuracy, and precision

---

## 🧠 How It Works

1. MRI images are loaded and preprocessed (resized, normalized).
2. A pre-trained CNN (VGG16) is loaded with ImageNet weights.
3. The model is fine-tuned on the tumor dataset using transfer learning.
4. The model predicts tumor presence on test data.
5. Results are visualized using metrics and plots.

---

## 📁 File Structure

Transfer-learning-for-tumor-detection/
├── Brain_tumor_detection.ipynb # Full training pipeline (loading data, VGG model, training, results)
├── VGG_16_(1).ipynb # Transfer learning with VGG16 model
└── README.md # This file

yaml
Copy
Edit

---

## 🔧 Requirements

Install dependencies with:

```bash
pip install tensorflow keras matplotlib numpy scikit-learn
