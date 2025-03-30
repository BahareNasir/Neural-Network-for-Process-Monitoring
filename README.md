# Neural-Network-for-Process-Monitoring
Early Warning System using Neural Networks
# 🚨 Early Warning System for High-Frequency Quality Abnormalities Detection Using Neural Networks

This repository presents a machine learning-based early warning system developed for detecting high-frequency quality abnormalities in a sugar production process. The approach combines **neural network classification**, **statistical monitoring**, and **multivariate control charts**.

## 🔍 Project Overview

This research was conducted in a sugar factory in Qazvin, Iran. The focus was on evaluating and predicting the quality of raw syrup by modeling the relationships between process variables using neural networks and monitoring residuals using control charts.

### Key Components:
- Input variables: Diffusion, bagasse extraction, pH (fresh water & diffusion), BX of water
- Output variables: BX and pH of raw syrup
- Binary classification using k-means clustering and neural networks
- Cascade forward and feedforward network evaluation
- EWMA and Shewhart control charts for process stability monitoring

## 📊 Methodology

1. **Data Preparation**
   - Data normalization (min-max scaling)
   - Correlation analysis and p-value test
   - Binary classification setup via elbow method and clustering (K-means)

2. **Neural Network Modeling**
   - Model training with cross-validation
   - Evaluation using confusion matrix, accuracy, and regression
   - Comparison of feedforward vs. cascade-forward networks
   - Final model selection based on MSE, MAE, and R²

3. **Control Charts Design**
   - EWMA control charts to monitor residuals of output variables (Y1, Y2)
   - Phase I and Phase II control limits applied

## 🧪 Techniques Used

- **Neural Network Classification & Regression**
- **K-means Clustering & Elbow Method**
- **Correlation & P-Value Analysis**
- **Confusion Matrix & Validation Metrics**
- **Multivariate Control Charts: EWMA / Shewhart**

## ⚙️ Tools & Technologies

- MATLAB
- Neural Network Toolbox
- Statistical analysis tools (corrcoef, p-value test, control charts)

## 📈 Results Summary

- **Cascade-forward network** outperformed feedforward with:
  - MSE = 0.01374
  - MAE = 0.08913
  - R² = 0.8056
- Control charts successfully flagged abnormal behavior in process variables

## 🧪 Applications & Implications

- Industrial quality monitoring
- Predictive maintenance
- Process optimization and early detection of operational faults

---

## 📬 Contact

For questions or collaboration:
**Bahare Nasir**  
**Email:** bahare.na@hotmail.com

