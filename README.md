# MLproject

🔍 Utility Consumption Forecasting on University Campus
📘 Overview
This project focuses on optimizing utility usage (electricity, gas, and water) across a university campus using predictive modeling. The aim is to improve efficiency, reduce waste, and support sustainability goals by transitioning from fixed-schedule systems to demand-driven operations.

📊 Dataset Description
Sources: University facilities consumption logs

Data Granularity: Hourly

Utility Categories: Electricity (Building and Submeter), Gas, and Water

Features:

Time-based (hour, day, month, holiday/weekend)

Building-specific (insulation, size, material)

Historical consumption and 24-hour rolling averages

🛠 Methodology
We used a multi-model forecasting approach:

Statistical Models: SARIMA, Exponential Smoothing

Machine Learning Models: Random Forest, XGBoost

Deep Learning Models: LSTM, Temporal Convolutional Networks (TCNs)

📏 Evaluation
Metric: Root Mean Square Error (RMSE)

Validation: Time-based cross-validation

📈 Results
Utility	Average Reduction
Electricity	42.3%
Gas	37.1%
Water	20.6%

Impact: Improved resource allocation and lowered utility bills.
