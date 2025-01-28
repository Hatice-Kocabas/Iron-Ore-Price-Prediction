# Iron Ore Price Prediction

This repository contains a project that predicts daily iron ore prices using machine learning techniques. The project evolves over three versions, with each version introducing additional features, optimizations, and analyses.

---

## Project Overview

Iron ore price prediction is a complex task influenced by various economic and financial factors. This project uses an **LSTM-based model** to perform daily price predictions. The project builds step-by-step with the following versions:

### **Version 1**
- **Features**:
  - Date  
  - Iron Ore Price  
  - Brent Oil Price  
  - USD Buying Rate  
  - USD Selling Rate  
  - CPI (Yearly % Change)  
  - CPI (Monthly % Change)  
- **Results**:  
  - Training RMSE: 0.0608  
  - Testing RMSE: 0.0925  

---

### **Version 2**
- **Added Features**:
  - Stock Market Values for VALE3  
  - Stock Market Values for BHP Group  
  - China's CPI (Yearly Change)  
- **Optimization**:  
  - Hyperparameter tuning for improved performance.  
- **Results**:  
  - Training RMSE: 0.0138  
  - Testing RMSE: 0.0279  

---

### **Version 3**
- **Sentiment Analysis**:
  - Financial news articles were analyzed using the **GPT-J model** to classify sentiment as "Increase" or "Decrease".  
  - Sentiment data was added as a feature to enhance prediction accuracy.  
- **Results**:  
  - Training RMSE: 0.0667  
  - Testing RMSE: 0.0898  

---

## Model Architecture

The project uses a **Long Short-Term Memory (LSTM)** neural network to capture temporal dependencies in the dataset. The architecture includes:
- LSTM Layers  
- Dense Layers  
- Dropout Layers for regularization  

---

