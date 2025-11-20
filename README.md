# 📊 Stock Market Analysis — Technical Indicators & Deep Learning Models

**Advanced Technical Analysis + Price Prediction using LSTM, N-BEATS & Temporal Fusion Transformer**

> This repository is part of a two-module research system. 🔗 For complete fundamental analysis, visit the second repo:  
> 👉 **[Stock-Market-Fundamental-Analysis](https://github.com/Naja24/Stock-Market-Fundamental-Analysis)**

---

## 🚀 Overview

This project focuses on **Technical Analysis** and **Machine Learning-based Stock Price Forecasting**. It includes:

- **Technical Indicators** (RSI, SMA, EMA, MACD)
- **Deep Learning Models** for Forecasting:
  - LSTM
  - LSTM + Attention
  - N-BEATS
  - Temporal Fusion Transformer (TFT)
- **End-to-end notebooks** covering:
  - Data Gathering
  - Data Preprocessing
  - Model Training
  - Advanced Architectures

---

## 📂 Repository Structure
```
Colab Files/
│
├── 1-data-Gathering.ipynb
├── 2-data-preprocessing.ipynb
├── 3-model-training.ipynb
├── 3.1-LSTM_with_attention_Mechanism.ipynb
├── 3.1-Model Training Using NBeats.ipynb
├── 3.2 Price Prediction usingTFT.ipynb
└── 3_2_Price_Prediction_usingTFT_corrected.ipynb
```

---

## 📊 Technical Indicators Implemented

### ✔ 1. SMA (Simple Moving Average)
Smooths price movement using past averages.

### ✔ 2. EMA (Exponential Moving Average)
Gives more weight to recent data → better responsiveness.

### ✔ 3. RSI (Relative Strength Index)
Measures momentum.
- **RSI < 30** → Oversold (buy zone)
- **RSI > 70** → Overbought (sell zone)

### ✔ 4. MACD (Moving Average Convergence Divergence)
Trend indicator using EMAs; identifies momentum shifts.

---

## 🤖 ML Models Used

### 1️⃣ LSTM (Long Short-Term Memory)
Captures long-range patterns in time-series.

### 2️⃣ LSTM with Attention
Improves interpretability by assigning higher weight to important time steps.

### 3️⃣ N-BEATS
State-of-the-art forecasting model from Facebook AI.

### 4️⃣ TFT — Temporal Fusion Transformer
Handles:
- Long sequences
- Seasonal patterns
- Multivariate inputs

**Best performing model across tests.**

---

## 🧱 Architecture
```
Input → Preprocessing → Windowing → Model (LSTM/N-BEATS/TFT) → Prediction → Evaluation → Visualization
```

---

## 🔧 How to Use

### 1. Clone the Repo
```bash
git clone https://github.com/Naja24/Stock-Market-Analysis.git
cd Stock-Market-Analysis
```

### 2. Upload notebooks to Google Colab
All files are optimized for Colab.

### 3. Run in Order
1️⃣ Data Gathering  
2️⃣ Preprocessing  
3️⃣ Model Training  
4️⃣ Advanced Experiments (LSTM + Attention, TFT)

---

## 📈 Sample Outputs

- Price forecast curves
- Error metrics (MAE, RMSE)
- Attention scores
- Feature importance (TFT)

---

## 🔗 Related Project (Highly Recommended)

This repo is **Part 1: Technical Analysis**.  

For **Part 2: Complete Fundamental + Technical + Sentiment System**, visit:  
👉 **[Stock-Market-Fundamental-Analysis](https://github.com/Naja24/Stock-Market-Fundamental-Analysis)**

---

## 📜 License

MIT License.

---

## 🙏 Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to check the [issues page](https://github.com/Naja24/Stock-Market-Analysis/issues).

---

## ⭐ Show Your Support

If you found this project helpful, please consider giving it a ⭐!

---

## 📧 Contact

For questions or collaborations, feel free to reach out via GitHub issues.
