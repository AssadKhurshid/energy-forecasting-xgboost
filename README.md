
# ⚡ Energy Consumption Forecasting with XGBoost (2025)

This project predicts **hourly energy demand** using time series data and machine learning (XGBoost). It's enhanced for 2025 best practices with lag features, holiday flags, and Colab compatibility.

## 📈 Preview of Output

<div align="center">
  <img src="https://raw.githubusercontent.com/AssadKhurshid/energy-forecasting-xgboost/refs/heads/main/Assad_Actual_vs_predition_Test.png" alt="Prediction Plot" width="600"/>
</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/AssadKhurshid/energy-forecasting-xgboost/refs/heads/main/Assad_Feature_importance.png" alt="Feature Importance" width="500"/>
</div>

---

## 📂 Dataset

- **Source**: Hourly energy consumption data  
- **File**: `AEP_hourly.csv`  
- **Path**: `/content/drive/MyDrive/Datasets/AEP_Hourly/AEP_hourly.csv`

> You must upload this file to your Google Drive or modify the path if running locally.

---

## 🚀 Run in Google Colab

Click below to open this notebook in Google Colab:

[![Open In Colab](https://colab.research.google.com/drive/17DpuOCjmz_vwFI3xq0TDL09pb7R89BKT#scrollTo=gbABmoh3Yvxp)

---

## 🔧 Features Created

- Hour, Day of Week, Month, Year, etc.
- **Holiday flag** (U.S.)
- **Lag features**: previous hour & previous 24 hours
- **Rolling stats**: rolling mean & std

---

## 📦 Requirements

- `xgboost`
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `holidays`
- Google Colab or Python 3.10+ environment

```bash
pip install xgboost holidays pandas matplotlib seaborn
```

---

## 📊 Model Performance

- **Model**: `XGBoostRegressor`
- **Metric**: RMSE
- **RMSE Score**: ~⚡ _{259.14}_ (on test set)

---

## 🧠 Next Steps

- Add weather data using external API
- Hyperparameter tuning with Optuna
- Deploy as live dashboard using Streamlit

---

## 🤝 Contributing

Feel free to open issues or submit pull requests!

---


