# 🏥 MediFlow Cloud – Hospital Resource Utilization & Readmission Tracker

## 📌 Project Overview
MediFlow Cloud is a cloud-native healthcare analytics project designed to analyze hospital resource utilization, patient readmission patterns, cost drivers, and patient distribution using Python and Power BI.

This project simulates a real-world healthcare analytics pipeline and provides insights for better hospital decision-making.

---

## 🎯 Business Objective
- Analyze 30-day readmission rates
- Understand patient distribution & hotspots
- Identify cost drivers across encounters
- Monitor Average Length of Stay (ALOS)
- Support data-driven hospital optimization

---

## 🏗️ Architecture
AWS-based architecture (simulated locally):

AWS S3 (Storage) → Data Cleaning (Pandas) → Feature Engineering → Power BI Dashboard

---

## 📊 Dashboard Pages

### 🔹 1. Overview
- Total Patients
- Total Encounters
- Avg Length of Stay (LOS)
- Readmission Rate
- Total Claim Cost
- High-level summary visuals

### 🔹 2. Readmission Analysis
- Readmission Rate by Age Group
- Readmission Rate by Encounter Type
- Procedure-based Readmission Analysis
- Detailed breakdown table

### 🔹 3. Cost Analysis
- Claim Cost by Encounter Class
- Claim Cost by Age Group
- LOS vs Claim Cost (Scatter Plot)
- Encounter-level cost table

### 🔹 4. Patient Distribution & Hotspots
- Geographic patient distribution (Map)
- Distribution by Encounter Class
- Distribution by Age Group

---

## 📂 Folder Structure
MediFlow-Cloud-Hospital-Resource-Utilization-Readmission-Tracker
│
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
├── dashboard/
├── images/
└── README.md

---

## 🧰 Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Power BI
- AWS S3 (conceptual)
- AWS IAM (conceptual)

---

## 🔍 Key Features
- Data cleaning and preprocessing
- Feature engineering (Age, LOS, Readmission)
- 30-day readmission calculation logic
- Interactive Power BI dashboard
- Map-based hotspot analysis
- Scatter analysis for cost vs LOS

---

## 💡 Key Insights
- Inpatient encounters have the highest LOS
- Elderly patients (65+) show higher readmission risk
- Total claim cost is highest for inpatient cases
- Most patient data is concentrated in one region (Massachusetts)
- Dataset contains only one hospital, limiting comparative analysis

---

## ⚠️ Limitations
- Single hospital dataset
- Limited geographic variation
- AWS services simulated using local tools

---

## ▶️ How to Run
1. Open the notebook in Jupyter/Colab
2. Run all cells for data cleaning & processing
3. Generate processed CSV files
4. Open Power BI file (.pbix)
5. Refresh dashboard visuals

---

## 📸 Dashboard Preview
(Add screenshots in the images folder)

---

## ⭐ Project Outcome
This project provides a complete end-to-end healthcare analytics solution, helping understand patient behavior, cost patterns, and readmission risks through interactive dashboards.
