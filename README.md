# Heart Attack Risk Prediction using Deep Learning  
A comparative deep-learning study analyzing heart-attack risk among individuals following **Indian** and **Western** dietary patterns.  
This repository contains all models, datasets, training logs, and results from **Review 1** (baseline deep model) and **Review 2** (improved deep neural network).

---

## 📌 Project Overview
This project predicts heart-attack risk using health indicators and region-specific dietary patterns. Two datasets were developed:

- **Indian Food–Integrated Heart Attack Dataset**
- **Western Food–Integrated Heart Attack Dataset**

Each dataset includes demographic, clinical, and nutrient information such as:
- Age, Sex, Chest Pain Type  
- Blood Pressure, Cholesterol, FBS, ECG  
- Heart Rate, Exercise Angina  
- Calories, Carbohydrates, Proteins, Fat, Sugar, Sodium  
- Target variable (Heart Attack Risk: 0/1)

The project was completed in two stages:
1. **Review 1 – Baseline Feedforward Deep Neural Network (4 hidden layers)**
2. **Review 2 – Improved Deep Neural Network with BN + Dropout + LR Scheduler**

---

## 📊 Methodology Summary

### **Review 1 – Baseline Deep Neural Network**
- 4 hidden layers  
- ReLU activation  
- Dropout regularization  
- Adam optimizer  
- Dataset-wise performance reported for both Indian and Western datasets  

### **Review 2 – Improved Deep Learning Model**
- 5 hidden layers  
- Batch Normalization  
- Dropout (0.3)  
- Learning Rate Scheduler  
- Better stability & smoother loss curves  
- Improved accuracy, recall, and ROC-AUC  

---

## 🔍 Key Results

### **Indian Dataset**
**Review 1**
- Accuracy: 0.9016  
- F1-Score: 0.90  
- ROC-AUC: 0.90  
- Test-set Risk: 54.10%  
- Predicted High-Risk: 54.10%

**Review 2**
- Accuracy: 0.9180  
- F1-Score: 0.9254  
- ROC-AUC: 0.9535  
- Test-set Risk: 54.10%  
- Predicted High-Risk: 54.10%

---

### **Western Dataset**
**Review 1**
- Accuracy: 0.7692  
- F1-Score: 0.77  
- ROC-AUC: 0.74  
- Test-set Risk: 69.23%  
- Predicted High-Risk: 61.54%

**Review 2**
- Accuracy: 0.7692  
- F1-Score: 0.8286  
- ROC-AUC: 0.8594  
- Test-set Risk: 69.23%  
- Predicted High-Risk: 61.54%

---

## 🛠️ Technologies Used
- Python  
- PyTorch  
- NumPy, Pandas  
- Scikit-learn  
- Matplotlib, Seaborn

---

