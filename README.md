# ML-Model-Monitoring-Dashboard

A Power BI dashboard designed to monitor, compare, and analyze the performance of multiple machine learning model versions deployed in production or testing environments.
It helps ML and Data Science teams ensure models continue to perform well, detect performance degradation, and support decision-making for model updates or retraining.


🧩 Key Features
Multi-Version Monitoring
Track and visualize the performance of multiple model versions (e.g., v1.0, v1.1, v2.0) at the same time.

Real-time KPI Tracking
KPIs like Accuracy, Precision, Recall, Prediction Volume, and Drift Score are aggregated and visualized clearly.

Model Performance Comparison
Side-by-side charts help easily compare different model versions across core evaluation metrics.

Accuracy and Drift Over Time
Trends are captured monthly to highlight when models start degrading, drifting, or require retraining.

Volume Analysis
Understand how many predictions each model version made and whether newer versions are more actively used.

Interactive Filters
Filters for model version and time periods allow focused analysis for specific investigations.

Drift Monitoring
Integration of drift scores helps identify if the data distribution has changed, indicating when models may become less reliable



Visual | Purpose
Average Accuracy / Precision / Recall Cards ------------| Quickly see high-level model health indicators.
Accuracy by Model Version (Pie Chart) -------------------| Understand each model's contribution to overall performance.
Accuracy Over Time (Line Chart) --------------------------| Spot trends and identify periods of accuracy degradation.
Comparing Models Side-by-Side (Bar Chart) -----------------| Direct metric comparison between model versions.
Predictions by Model Version (Bar Chart) ------------------| See distribution of prediction load across versions.

 KPIs (from Dashboard)
Average Accuracy: 0.84

Average Precision: 0.80

Average Recall: 0.73

Total Predictions: 109,000

Average Drift Score: 0.48

Best Performing Model Version: v1.0





