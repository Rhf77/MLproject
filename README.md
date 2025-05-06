# 🔌 Utility Consumption Forecasting on a University Campus

## 📌 Project Overview

This project aims to optimize utility resource consumption across a university campus through predictive modeling. Leveraging time-series forecasting and building-level metadata, we enable dynamic, demand-based utility scheduling to improve energy efficiency, reduce operational waste, and support long-term sustainability initiatives.

---

## 📂 Dataset Summary

The dataset integrates smart meter readings and infrastructure metadata, providing granular, real-world insights into utility usage.

### Utilities Monitored
- ⚡ Electricity (building-level and submetered)
- 🔥 Gas
- 💧 Water

### Granularity
- Hourly consumption records

### Building Attributes
- Year of construction  
- Building type (academic, residential, lab, cafeteria)  
- Size, materials, insulation quality  

### Temporal Features
- Hour, day, month  
- Weekends and holidays  
- Previous hour/day usage  
- 24-hour rolling averages  

---

## 🧠 Methodology

To capture the complexity and temporal nature of utility data, we employ a hybrid modeling strategy combining statistical, machine learning, and deep learning approaches.

### 1. Baseline Statistical Models
- Seasonal ARIMA (SARIMA)  
- Exponential Smoothing  

### 2. Machine Learning Models
- Random Forest Regressor  
- XGBoost Regressor  

### 3. Deep Learning Models
- Long Short-Term Memory Networks (LSTM)  
- Temporal Convolutional Networks (TCN)  

---

## ⏳ Validation Strategy

- **Time-based cross-validation**
- **Evaluation metrics**: RMSE, MAE, R²

---

## 📉 Results

| Utility     | Reduction (%) |
|-------------|----------------|
| Electricity | 42.3%          |
| Gas         | 37.1%          |
| Water       | 20.6%          |

> Consumption was normalized using 2019 baseline data. A ±2.5% confidence interval applies.

---



## 🛠 Technology Stack

- **Languages**: Python  
- **Libraries**: `pandas`, `NumPy`, `scikit-learn`, `XGBoost`, `TensorFlow/Keras`, `statsmodels`  
- **Visualization**: `matplotlib`, `seaborn`  
- **Development**: Jupyter Notebook, Google Colab  

---

## 🎓 Academic Contribution

This project supports research in smart building energy efficiency by:

- Demonstrating multi-horizon forecasting  
- Comparing statistical, ML, and DL approaches  
- Leveraging high-resolution real-world datasets  

---



## 📄 License

This project is intended for academic and research purposes only. For reuse, collaboration, or licensing inquiries, please contact the project maintainers.
