
# ⚡ Energy Consumption Forecasting with XGBoost (2025)

This project predicts **hourly energy demand** using time series data and machine learning (XGBoost). It's enhanced for 2025 best practices with lag features, holiday flags, and Colab compatibility.

## 📈 Preview of Output

<div align="center">
  <img src="https://github.com/your-username/energy-forecasting-xgboost/raw/main/images/prediction_plot.png" alt="Prediction Plot" width="600"/>
</div>

<div align="center">
  <img src="https://github.com/your-username/energy-forecasting-xgboost/raw/main/images/feature_importance.png" alt="Feature Importance" width="500"/>
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

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/your-username/energy-forecasting-xgboost/blob/main/energy_forecasting.ipynb)

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
- **RMSE Score**: ~⚡ _{your_score_here}_ (on test set)

---

## 🧠 Next Steps

- Add weather data using external API
- Hyperparameter tuning with Optuna
- Deploy as live dashboard using Streamlit

---

## 🤝 Contributing

Feel free to open issues or submit pull requests!

---

## 📜 License

MIT License. See `LICENSE` file for details.
