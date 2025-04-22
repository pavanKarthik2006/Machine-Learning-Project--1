System Threat Forecaster: ML-based Malware Prediction using Telemetry Data
A lightweight machine learning project to forecast potential malware threats on a system using telemetry data such as process usage, network activity, and system behavior logs. This project aims to demonstrate how telemetry-driven threat intelligence can be automated with supervised ML models.


📊 Dataset
Synthetic or open-source telemetry datasets (e.g., Microsoft Malware Prediction on Kaggle)

Labels: 0 (clean) or 1 (infected)

Features: CPU usage, process tree behavior, DLL loads, registry changes, etc.

ML Workflow
Data Preprocessing

Handle missing values

Normalize/scale numeric features

Encode categorical data

Exploratory Data Analysis

Correlation heatmaps

Feature importance plots

Class distribution analysis

Model Training

Baseline: Logistic Regression

Advanced: Random Forest, XGBoost, or LightGBM

Metrics: Accuracy, ROC-AUC, F1-score

Evaluation & Logging

Confusion Matrix

ROC curve

Save model + metrics



