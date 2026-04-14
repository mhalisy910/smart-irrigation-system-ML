# 🌱 Smart Irrigation System using Machine Learning and Crop-Specific Modeling

## 📌 Overview
This project presents a smart irrigation decision system that combines statistical analysis and machine learning to optimize irrigation strategies for different crops.

Unlike traditional systems that rely on fixed thresholds, this approach dynamically adapts irrigation decisions based on crop-specific environmental conditions.

---

## 🧠 Key Features

- Crop-specific irrigation thresholds using statistical measures (Q1, Q3, median)
- Hybrid decision system combining rule-based logic and machine learning
- Multiple ML models evaluated (Random Forest, XGBoost, SVM, Decision Tree)
- Feature engineering for improved prediction accuracy
- Visualization of model performance and decision behavior

---

## ⚙️ Methodology

### 1. Data Processing
- Dataset includes soil nutrients (N, P, K), temperature, humidity, rainfall, and crop type
- Data cleaning and preprocessing using pandas

### 2. Dynamic Irrigation Modeling
- For each crop:
  - Humidity threshold = Q1
  - Temperature threshold = Q3
  - Rainfall threshold = median
- Irrigation decision based on adaptive conditions

### 3. Machine Learning
Models used:
- Random Forest
- XGBoost (best performing)
- SVM
- Decision Tree

### 4. Evaluation
- Accuracy and F1-score
- Confusion Matrix
- Model comparison

---

## 📊 Results

| Model | Accuracy |
|------|--------|
| XGBoost | ~0.89 |
| Random Forest | ~0.87 |
| Decision Tree | ~0.83 |
| SVM | ~0.66 |

---

## 🚀 Future Work

- Integration with IoT sensors for real-time irrigation
- Time-series modeling
- Deep learning approaches
- Deployment as a real-time decision system

---

## 🧑‍💻 Author
- Developed as part of a research-oriented smart agriculture system