# Federated Learning for Network Congestion Prediction (4G/5G)

## 📌 Overview
This project explores the use of **Federated Learning (FL)** to predict **network congestion levels** across multi-carrier 4G/5G environments. Instead of pooling all data into a central server, FL allows training models across distributed telecom carriers, preserving **data privacy** while achieving strong predictive performance.

## 🛠 Tools & Libraries
- Python  
- Pandas, NumPy  
- LightGBM  
- Flower (Federated Learning framework)  
- Scikit-learn  
- Matplotlib, Seaborn  

## 📊 Dataset
- Realistic 5G network dataset (`5g_network_data.csv`) with 21 features.  
- Includes signal quality metrics, device/network attributes, and a target variable: **Network Congestion Level (High, Medium, Low)**.  
- No missing values.  

## ⚙️ Implementation
- Built a **centralized baseline model** using LightGBM.  
- Implemented **federated clients** (each representing a telecom carrier).  
- Simulated training with Flower framework.  
- Compared centralized vs federated performance.  

## 🏆 Results
- Achieved high classification accuracy in both centralized and federated settings.  
- Demonstrated that **federated models can achieve comparable performance** while preserving **privacy**.  

## 🚀 Key Takeaways
- Federated Learning is effective for **telecom network congestion prediction**.  
- Enables collaboration between carriers without sharing raw data.  
