# 📡 Telecom Explainable AI Platform

🚀 End-to-end AI-powered telecom analytics platform for:
- 📊 KPI Analysis  
- 🤖 Anomaly Detection  
- 🧠 Explainable AI (SHAP-based RCA)  
- 🚨 Real-time Alerting  
- 📈 Dashboard Integration  

---

## 🧠 Problem Statement

Modern telecom networks generate massive KPI data such as:

- Call Drop Rate (DCR)
- Call Setup Success Rate (CSSR)
- Latency, SINR, Throughput

🔴 Challenges:
- Manual monitoring is slow  
- Root cause identification is complex  
- Alerts lack explanation  

✅ This project solves it using AI:
- Automatically detects anomalies  
- Explains *why* issues occur  
- Sends real-time alerts  
- Enables data-driven decisions  

---

## 🏗️ Architecture Overview

images/architecture_diagram.png

---

## 🤖 AI Pipeline

images/pipeline_flow.png

---

## 🚨 Real-Time Alert Workflow

images/alert_workflow.png

---

## 🔥 Key Features

✅ AI Anomaly Detection
✅ Explainable RCA (SHAP)
✅ Real-Time Alerting
✅ Dashboard Integration

---

## 📁 Project Structure

telecom-ai-explainable-platform/
│
├── data/
│   └── telecom_kpi_sample_dataset.csv
│
├── notebooks/
│   ├── telecom_kpi_analysis.ipynb
│   ├── anomaly_detection.ipynb
│   └── shap_ai_rca.ipynb
│
├── src/
│   ├── main_pipeline.py
│   ├── alerting_pipeline.py
│   └── utils.py
│
├── dashboard/
│   └── powerbi_dashboard_dataset.csv
│
├── images/
│   ├── architecture.png
│   ├── shap_output.png
│   └── pipeline_flow.png
│
├── requirements.txt
├── README.md
└── .gitignore
---

## ⚙️ Installation

pip install -r requirements.txt

---

## 🚀 Usage

Run pipeline:
python src/main_pipeline.py

Run alerts:
python src/alerting_pipeline.py

---

## 👤 Author

Sowmiya Chidambaram

---

## ⭐ Star this repo if you like it!
