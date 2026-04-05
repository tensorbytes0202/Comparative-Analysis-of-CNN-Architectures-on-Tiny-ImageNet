# 🧠 Comparative Analysis of CNN Architectures on Tiny-ImageNet

This project presents a comprehensive comparison of different deep learning architectures for image classification on the Tiny-ImageNet dataset. The models evaluated include a custom CNN, ResNet18, and MobileNetV2.

---

## 🚀 Project Overview

The goal of this project is to analyze and compare the performance of:

- Custom Convolutional Neural Network (CNN)
- ResNet18 (Residual Network)
- MobileNetV2 (Lightweight Architecture)

Evaluation is performed using multiple metrics such as Accuracy, Precision, Recall, F1-score, Confusion Matrix, and Top Predictions.

---

## 📂 Project Structure

![Project Structure](images/project_structure.png)

---

## 📊 Model Accuracy Comparison

![Accuracy Comparison](images/accuracy.png)

- CNN shows lower performance due to limited feature extraction capacity.
- ResNet performs best due to residual connections.
- MobileNet provides a good trade-off between performance and efficiency.

---

## 🔍 Confusion Matrix (ResNet)

![Confusion Matrix](images/confusion_matrix.png)

- Diagonal concentration shows correct predictions.
- Sparse distribution indicates class confusion due to dataset complexity.

---

## 📈 Multi-Metric Comparison

![Multi Metrics](images/multi_metrics.png)

- ResNet dominates across Accuracy, Precision, and Recall.
- MobileNet performs competitively with lower computational cost.
- CNN underperforms compared to pretrained models.

---

## 📊 Performance Metrics (Precision, Recall, F1)

![Metrics](images/metrics.png)

- Precision is relatively higher than recall.
- Low recall indicates difficulty in capturing all true classes.
- F1-score reflects imbalance in predictions.

---

## 🖼️ Sample Predictions

![Predictions](images/predictions.png)

- Visual examples of model predictions on validation data.
- Shows both correct and incorrect classifications.

---

## 📑 Classification Report
