# Bitcoin (BTC) Price Prediction & Interpretability with LIME

A machine learning project focused on predicting Bitcoin price trends and interpreting model decisions using **LIME (Local Interpretable Model-agnostic Explanations)** to bring transparency to black-box financial forecasting models.

---

## 📌 Project Overview

Cryptocurrency price forecasting often suffers from black-box complexity, where high-performing models lack interpretability. This project combines exploratory data analysis, time-series feature engineering, and predictive modeling with **Explainable AI (XAI)** techniques to understand *why* specific predictions are made.

### Key Objectives:
- **Predictive Modeling:** Train and evaluate machine learning models on historical Bitcoin market data.
- **Explainability (XAI):** Apply LIME to explain individual predictions, identifying which technical features (e.g., volume spikes, momentum shifts, moving average crossovers) drove specific model outputs.
- **Formal Analysis:** Document findings, model behavior, and feature attribution in an accompanying analytical report.

---

## 📂 Repository Contents

| File | Description |
| :--- | :--- |
| **`Bitcoin_price_prediction(v3).ipynb`** | End-to-end Jupyter Notebook covering data preprocessing, feature engineering, model training, evaluation, and LIME explanation visualizations. |
| **`Bitcoin Price Prediction Report with LIME Explanation.docx`** | Detailed write-up and report analyzing model performance, methodology, and interpretability insights. |

---

## ⚙️ Methodology & Pipeline

1. **Data Ingestion & Cleaning:** Historical OHLCV Bitcoin price action preprocessing and temporal ordering.
2. **Feature Engineering:** Calculation of key statistical and technical indicators (trend, momentum, volatility).
3. **Model Training:** Fitting predictive models on historical time-series partitions.
4. **LIME Explanations:** Local surrogate modeling to evaluate feature importance and attribution for specific bullish/bearish predictions.

---

## 🛠 Tech Stack

- **Language:** Python
- **Explainable AI:** `lime`
- **Data & Modeling:** `pandas`, `numpy`, `scikit-learn`
- **Visualization:** `matplotlib`, `seaborn`
- **Environment:** Jupyter Notebook

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone [https://github.com/ChandlerD1025/Bitcoin-Price-Predictor.git](https://github.com/ChandlerD1025/Bitcoin-Price-Predictor.git)
cd Bitcoin-Price-Predictor

```

### 2. Install Required Packages

```bash
pip install pandas numpy scikit-learn matplotlib seaborn lime jupyter

```

### 3. Run the Notebook

Launch Jupyter to explore the code, model training, and explanation outputs:

```bash
jupyter notebook "Bitcoin_price_prediction(v3).ipynb"

```

---

## ⚖️ Disclaimer

This repository is for **educational and research purposes only**. Nothing here constitutes investment or financial advice.

```

```
