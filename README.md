# 🐱🐶 Cat vs Dog Image Classifier using SVM

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b1/VAN_CAT.png/480px-VAN_CAT.png" width="120"/>
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b3/Dog_icon.png/480px-Dog_icon.png" width="120"/>
</p>

<p align="center">
  <b>A Machine Learning project using Support Vector Machines (SVM) to classify images of Cats and Dogs with HOG features.</b><br>
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/OpenCV-4.x-success?style=flat-square" />
  <img src="https://img.shields.io/badge/Sklearn-1.x-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square" />
</p>

---

## 🚀 Project Overview

🎯 **Goal:** Classify 25,000 cat and dog images using traditional Machine Learning (SVM).  
🧠 **Model:** Support Vector Machine (SVM) with **RBF Kernel**  
📊 **Feature Extractor:** Histogram of Oriented Gradients (HOG)

---

## 📈 Final Performance

| Metric           | Cat Class | Dog Class |
|------------------|-----------|-----------|
| **Precision**     | 75%       | 73%       |
| **Recall**        | 72%       | 76%       |
| **Accuracy**      | **74.15%** (on 5,000 test images) |

---

## 🧩 Dataset Summary

- **Total Images**: 25,000  
- **Train Directory**:
  - `train/cat/`: 12,500 images
  - `train/dog/`: 12,500 images  
- **Test Directory**: `test1/` *(Kaggle test set without labels)*

---

## 🛠 How It Works

### ✅ Preprocessing
- Images resized to **64x64**
- Converted to grayscale
- Flattened into 1D vectors

### ✅ Feature Extraction
- HOG descriptors extracted using OpenCV

### ✅ Classification
- Trained an SVM (`SVC`) model with RBF kernel on 10,000 samples  
- Evaluated on 5,000 test samples using accuracy and classification report

---

