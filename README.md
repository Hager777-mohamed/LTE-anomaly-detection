# 📡 AI-Powered Anomaly Detection in 4G LTE Networks

This repository contains the complete graduation project:  
**Anomaly Detection in LTE KPI Time Series using Hybrid AI Models + Geo-Spatial Analysis**

🎓 **Project Type**: Graduation Project  
🏫 **Institute**: Information Technology Institute (ITI)  
🧑‍🏫 **Supervisors**: Dr. Mahmoud Abdelaziz, Eng. Meriham Rizk  
📅 **Duration**: 2024–2025  
🌍 **Dataset**: Real LTE KPI data provided by [Digis Squared]

---

## 🚀 Overview

We built an intelligent anomaly detection system for mobile network KPIs using a hybrid of statistical and deep learning models. The goal was to detect abnormal behavior in LTE cell performance using AI, interpret the anomalies, and present results through a fully interactive web dashboard.

---

## 🧠 Key Components

### ✅ Detection Models
- STL + Z-Score Residuals
- Facebook Prophet (Forecasting + Residual Analysis)
- Local Outlier Factor (LOF)
- Autoencoder (Unsupervised Deep Learning)
- Bi-LSTM (Supervised Sequence Classifier)
- **Hybrid Voting Mechanisms** for ensemble detection

### 📍 Geo-Spatial Module
- Cluster and filter LTE cells based on GPS coordinates
- Support for region-based filtering and frequency band selection (L07, L18, L21)
- Interactive map (Folium)

### 💬 LLM Summary Generator
- Uses a language model to generate plain-language explanations of anomalies
- Offers KPI insights, trends, and optional recommendations

### 🖥 Web App (Streamlit)
- Visualize anomaly detections across KPIs, cells, time
- Filter by site, region, anomaly type, model
- Compare models and export results

---

## 📊 Tools & Technologies

- **Languages**: Python
- **ML/Stats**: Prophet, STL, LOF, Autoencoder, Bi-LSTM
- **Visualization**: Matplotlib, Plotly, Folium
- **UI**: Streamlit
- **Others**: Pandas, NumPy, Scikit-learn, TQDM

---

## 📂 Repository Structure

