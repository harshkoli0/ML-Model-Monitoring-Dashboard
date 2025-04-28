# ML-Model-Monitoring-Dashboard

# ML Model Monitoring Dashboard

[![Power BI](https://img.shields.io/badge/Power%20BI-Visualization-blue)](#)
[![Dashboards](https://img.shields.io/badge/Dashboards-Analytics-yellow)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

---


## 📷 Dashboard Preview
<img src="Dashboard.png" width="800">


---



# overview

A Power BI dashboard designed to monitor, compare, and analyze the performance of multiple machine learning model versions deployed in production or testing environments.
It helps ML and Data Science teams ensure models continue to perform well, detect performance degradation, and support decision-making for model updates or retraining.


# Key Features
1.Multi-Version Monitoring
Track and visualize the performance of multiple model versions (e.g., v1.0, v1.1, v2.0) at the same time.

2.Real-time KPI Tracking
KPIs like Accuracy, Precision, Recall, Prediction Volume, and Drift Score are aggregated and visualized clearly.

3.Model Performance Comparison
Side-by-side charts help easily compare different model versions across core evaluation metrics.

4.Accuracy and Drift Over Time
Trends are captured monthly to highlight when models start degrading, drifting, or require retraining.

5.Volume Analysis
Understand how many predictions each model version made and whether newer versions are more actively used.

6.Interactive Filters
Filters for model version and time periods allow focused analysis for specific investigations.

7.Drift Monitoring
Integration of drift scores helps identify if the data distribution has changed, indicating when models may become less reliable


## 📏 Metrics Tracked

- **Accuracy** 🎯: Percentage of correctly predicted labels (e.g., 84% correct predictions overall).
- **Precision** 🏹: Out of all positive predictions, how many were actually positive (e.g., 80% precision).
- **Recall** 🧲: Out of all actual positives, how many were predicted correctly (e.g., 73% recall).
- **Drift Score** 🌪️: A measure of data distribution shift; high drift suggests need for model retraining (e.g., 0.48 drift score).
- **Total Predictions** 📈: Number of samples classified by the model (e.g., 109,000 predictions).
- **Best Performing Model** 🏆: Model version with the best overall accuracy, precision, and recall (e.g., v1.0).



 # KPIs (from Dashboard)
Average Accuracy: 0.84

Average Precision: 0.80

Average Recall: 0.73

Total Predictions: 109,000

Average Drift Score: 0.48

Best Performing Model Version: v1.0





