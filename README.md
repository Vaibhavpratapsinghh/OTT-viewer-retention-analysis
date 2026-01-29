# 🎬 Viewer Retention Analysis in OTT Platforms

![Project Badge](https://img.shields.io/badge/Winter%20Consulting-IITG%20C%26A-blue?style=for-the-badge)

## 🎓 Program Information

**Program:** Winter Consulting Capstone 2025  
**Organized By:** Consulting & Analytics Club (C&A), IIT Guwahati  

---

## 🚀 Project Overview

This project analyzes episode-level engagement data from an OTT streaming platform to understand the key drivers of viewer drop-off and retention risk. The goal is to translate data insights into actionable business recommendations that improve early-season viewer retention.

---

## 📌 Project Objective

- Identify patterns that explain why viewers disengage during early episodes.
- Analyze how episode characteristics such as duration, cognitive load, and pacing influence drop-off.
- Segment episodes based on retention risk.
- Recommend practical, data-backed interventions to improve engagement.

---

## 📂 Dataset Overview

- Each row represents a single episode.
- Contains behavioral and content attributes such as:
  - Episode number and duration
  - Average watch percentage
  - Drop-off probability
  - Pause and rewind activity
  - Cognitive load and pacing indicators
  - Genre and retention risk label
- Dataset is designed for realistic OTT retention analysis.

> Note: Viewer behavior data is synthetically generated for educational purposes.

---

## 🛠️ Tools & Technologies

- Python  
- Pandas  
- Matplotlib  
- Google Colab  

SQL-style aggregations (grouping, filtering, metrics) were implemented using Python.

---

## 🔍 Methodology

1. **Data Loading & Cleaning**
   - Loaded CSV dataset into Pandas.
   - Selected relevant analytical columns.

2. **Exploratory Data Analysis (EDA)**
   - Drop-off trend across episode progression.
   - Impact of cognitive load on drop-off probability.
   - Relationship between episode duration and watch completion.

3. **Segmentation**
   - Episodes grouped into Low, Medium, and High retention risk segments.
   - Compared engagement behavior across segments.

4. **Insights & Recommendations**
   - Identified key drivers of early viewer drop-off.
   - Proposed feasible interventions aligned with product and content constraints.

---

## 📊 Key Insights

- Viewer drop-off increases across episode progression, especially in early episodes.
- Episodes with higher cognitive load exhibit significantly higher drop-off.
- Longer episode durations correlate with lower completion rates.
- Retention drivers differ across episode segments.

---

## ✅ Recommendations

- Reduce cognitive load in early episodes to improve onboarding.
- Optimize episode duration by splitting or reordering long episodes.
- Introduce short recaps or contextual prompts in high-risk episodes.

---

## 📈 Success Metrics

- Primary: Episode Completion Rate  
- Supporting:
  - Drop-off probability before Episode 3
  - Average watch percentage

---

## 📁 Project Structure

📦 ott-viewer-retention-analysis
┣ 📄 ott_viewer_dropoff_retention_us_v1.0.csv
┣ 📓 analysis_notebook.ipynb
┣ 📄 Viewer_Retention_Analysis_in_OTT_Platforms_Report.pdf
┗ 📄 README.md

---

## 🚀 How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Upload the dataset file.
3. Run all cells to reproduce analysis and charts.

---

## 📬 Contact

- [LinkedIn](https://www.linkedin.com/in/vaibhav-pratap-singh-nitjsr)

---

⭐ **If you found this project insightful, consider giving it a star!**
