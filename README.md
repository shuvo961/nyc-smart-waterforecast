# Smart Water Forecasting and Efficiency Dashboard 💧📊

This project presents a cloud-based predictive analytics platform for forecasting urban water costs, detecting anomalies, and enabling interactive simulations—developed using AWS infrastructure and machine learning models. The use case focuses on New York City (NYC), where rising demand and aging infrastructure make proactive water management a critical challenge.

---

## 🚀 Project Overview

Urban water systems, especially in high-density cities like NYC, often suffer from reactive planning and limited tools for forecasting or anomaly detection. This project addresses those gaps by integrating:

- **Amazon Web Services (AWS)** for scalable data engineering and visualization,
- **Machine Learning models** (Prophet, XGBoost, Isolation Forest) for forecasting and anomaly detection,
- **Interactive dashboards** using **AWS QuickSight** to support dynamic scenario simulations.

---

## 🧠 Core Features

- 📈 **Time Series Forecasting**: Borough-level water cost prediction through 2026 using Prophet and XGBoost.
- 🚨 **Anomaly Detection**: Automatic identification of abnormal billing behavior using Isolation Forest.
- 🎛️ **Interactive Dashboard**: Real-time data visualization and “what-if” simulations via AWS QuickSight.
- ☁️ **Cloud-Native Pipeline**: Built with AWS S3, Glue, SageMaker, and QuickSight for scalable ETL, modeling, and presentation.

---

## 🧰 Tech Stack

- **Amazon S3** – Dataset storage
- **AWS Glue** – Data preprocessing and ETL
- **Amazon SageMaker** – Model training and hosting
- **Google Colab / JupyterLab** – Python development
- **AWS QuickSight** – Interactive dashboards
- **Python Libraries**: `pandas`, `prophet`, `xgboost`, `scikit-learn`, `matplotlib`

---

## 📊 Results Summary

- **Brooklyn** and **Manhattan** forecasted to lead in water cost by 2026 (>$110M).
- **Anomalies detected** between 2021–2024 helped identify data/reporting inconsistencies.
- **Simulation tools** empower users to estimate cost impacts of conservation behaviors.

---
