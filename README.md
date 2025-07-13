# Behavioural Transaction Analysis for Fraud Detection

A Lean Six Sigma Black Belt project applying the DMAIC methodology to enhance fraud detection accuracy by analyzing transactional behavior in a synthetic dataset of 5 million financial records.

---

## 📌 Project Summary

This project aims to reduce missed frauds (false negatives) by identifying and quantifying behavioral indicators such as velocity spikes, spending deviations, device shifts, and geo-anomalies. Using non-parametric statistical analysis and control charts, the process was improved to achieve higher fraud detection performance and greater stability.

---

## 📂 Project Contents

- `/presentation/` : PowerPoint slides detailing each phase of the DMAIC framework  
- `README.md` : Summary of project purpose, methodology, and insights  

---

## 📊 Key Highlights

- Improved fraud detection score from **~85 to 96.3**  
- Used **Mann-Whitney U Test** for non-normal metrics (e.g., `velocity_score`)  
- Identified `velocity_score` and `geo_anomaly_score` as statistically significant fraud indicators  
- Implemented process control to maintain sustainability through periodic retraining and alerts  

---

## 🛠 Tools & Techniques

- DMAIC Framework  
- Anderson-Darling Test  
- Mann-Whitney U & Spearman Correlation  
- SIPOC, Fishbone Diagram, CTQ Tree  
- I-MR Control Charts (Before vs. After)  

---

## 📜 License

MIT License – reuse permitted with attribution.

---

## ✒️ Attribution

**K.S. Manjunath created this project** as part of his Lean Six Sigma **Black Belt** learning journey.  
All content, analysis, and methodology reflect original work using simulated financial data.  
Feel free to reference or build upon this project — just remember to credit the author.  
Unauthorized replication or plagiarism is discouraged and may result in takedown action.

---

## 🔗 Next Steps (Optional Ideas)

- Integrate machine learning for real-time fraud prediction  
- Develop a dashboard for live fraud monitoring  
- Compare detection rate against industry benchmarks  

---
