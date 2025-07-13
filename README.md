# Behavioural Transaction Analysis for Fraud Detection

This project applies the Lean Six Sigma DMAIC framework to improve the fraud detection process in financial transactions using behavioral anomaly analysis.

---

## 📌 Project Overview

**Objective:** Improve fraud detection accuracy by identifying key behavioral indicators and minimizing missed frauds (false negatives) in a synthetic financial transaction dataset of 5 million records.

**Methodology:**  
Lean Six Sigma DMAIC  
- Define  
- Measure  
- Analyze  
- Improve  
- Control

---

## 📊 Dataset

- **Size:** 5 million synthetic financial transactions  
- **Features:**  
  - `velocity_score`, `spending_deviation_score`, `geo_anomaly_score`  
  - Transaction time, location, device info, payment channel, fraud label

---

## 📈 Key Findings

- `velocity_score` and `geo_anomaly_score` are **strong indicators** of fraud (Mann-Whitney U test, p < 0.005)  
- **Process improvement raised fraud detection score** from 85 to 96.3  
- Reduced variation and all post-improvement metrics within control limits  
- Independent contributions confirmed via Spearman correlation

---

## 🛠 Tools & Techniques Used

- Anderson-Darling Normality Test  
- Mann-Whitney U Test  
- Spearman Correlation  
- Fishbone Diagram, SIPOC, CTQ Tree  
- I-MR Control Charts (Before vs. After)

---

## 📂 Project Artifacts

- [Financial Fraud Detection – Project Presentation (PPTX)](./Financial%20Fraud%20Detection.pptx)  
- [Problem Description](./problem%20description.docx)

---

## 🧠 Reflection

This project showcases end-to-end process improvement using data-driven behavioral analytics in the finance domain. It highlights capabilities in fraud pattern recognition, root cause analysis, and sustainable control design.

---

## 📌 Next Steps

- Incorporate machine learning models for enhanced detection  
- Build a real-time monitoring dashboard (Tableau / Power BI)  
- Compare performance against industry benchmarks

---
