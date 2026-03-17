# Self-Supervised-Learning-for-Anomaly-Detection-in-System-Logs-
📘 Project Description

This project focuses on detecting anomalies in system logs using self-supervised learning techniques. It analyzes large volumes of log data and automatically identifies abnormal patterns without requiring labeled data. The system combines TF-IDF for feature extraction, FastICA for dimensionality reduction, HDBSCAN for clustering-based pseudo labeling, and a GRU model to capture sequential log behavior and detect anomalies efficiently.

⚙️ How It Works

-Log data is collected and preprocessed into structured format
-Text logs are converted into numerical features using TF-IDF
-FastICA reduces dimensionality for better pattern extraction
-HDBSCAN clusters logs and generates pseudo labels (normal/anomaly)
-A GRU model is trained on these patterns to learn log sequences
-The model predicts anomalies based on deviations from normal behavior

📊 Dataset Insights

-Dataset used: HDFS Log Dataset
-Contains large-scale system logs generated from distributed systems
-Includes log messages, event templates, and system activity details
-High volume and unstructured nature make manual analysis difficult
-Shows patterns of normal operations and rare anomalous events
-Suitable for testing scalability and real-world anomaly detection performance


------------------------THANK YOU--------------------------
