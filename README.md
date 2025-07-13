# Behavioural Transaction Analysis for Fraud Detection

A Lean Six Sigma Black Belt project applying the DMAIC methodology to enhance fraud detection accuracy by analyzing behavioral transaction patterns in a 10,000-record sample from a synthetic dataset of 1 million financial records.

---

## 📌 Project Summary

This project aims to reduce missed frauds (false negatives) by identifying key behavioral indicators such as transaction velocity, spending anomalies, geo-location mismatches, and device/IP changes. Using non-parametric hypothesis testing and control charts, the team implemented improvements that significantly enhanced detection accuracy and process stability.

---

## 📂 Project Contents

- `/presentation/`: PowerPoint slides detailing the full DMAIC journey  
- `README.md`: Summary of methodology, statistical tools used, and outcomes  

---

## 📊 Key Highlights

- Used a **10,000-transaction sample** from a larger synthetic 5M-record dataset  
- Identified `velocity_score` and `geo_anomaly_score` as statistically significant indicators (p < 0.005)  
- Improved detection score from **~85 to 96.3** after implementing control rules  
- Reduced variation; post-improvement results showed all points within control limits  
- Root causes included erratic velocity, abnormal spending, device/IP changes, and high geo-anomaly scores

---

## 🛠 Tools & Techniques

- DMAIC Framework  
- Anderson-Darling Normality Test  
- Mann-Whitney U Test  
- Spearman Correlation Analysis  
- SIPOC, CTQ Tree, Fishbone Diagram  
- I-MR Control Charts (Before vs. After)  
- Baseline & post-improvement comparison dashboards  

---

## 📜 License

MIT License – reuse permitted with attribution.

---

## ✒️ Attribution

**K.S. Manjunath created this project** as part of his Lean Six Sigma **Black Belt** learning journey.  
All content, analysis, and structure reflect original work using simulated data.  
You are welcome to reference or build upon this work, but please give appropriate credit.  
Plagiarism or unauthorized replication is discouraged and may result in takedown reporting.

---

## 🔗 Next Steps (Optional)

- Integrate ML algorithms for real-time fraud detection  
- Extend analysis to the full 1M-record dataset  
- Build automated dashboards for continuous monitoring  
- Benchmark detection performance against industry solutions  

---
