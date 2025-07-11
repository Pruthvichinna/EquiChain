# 🌱 EqualChain – ESG + DEI Supplier Intelligence Platform

**Team EqualChain | Walmart Sparkathon 2025**

EqualChain is an AI-powered dashboard that empowers Walmart and other retail giants to make data-driven, ethical, and sustainable supplier decisions.  
Our platform evaluates suppliers based on **Environmental**, **Social**, and **Governance (ESG)** metrics combined with **Diversity, Equity, and Inclusion (DEI)** indicators — helping organizations align with their sustainability and inclusion goals.

---

## 🧠 Problem Statement

Walmart is under increasing pressure to:

- Improve **supplier sustainability**
- Ensure **ethical sourcing**
- Enhance **diversity and inclusion**
- Streamline large-scale **supplier evaluations**

However, no centralized tool currently exists to **score, filter, and visualize** thousands of suppliers based on **CO₂ emissions**, **packaging**, **certifications**, and **ownership diversity**.

---

## ✅ Our Solution

EqualChain automatically:

- ✅ Merges and cleans multiple supplier datasets
- ✅ Scores suppliers using ESG + DEI metrics
- ✅ Provides powerful filtering options and visual dashboards
- ✅ Enables real-time decision-making and supplier rankings
- ✅ Supports exportable reports and maps (if geolocation is available)

---

## 🖥️ Tech Stack

| Layer         | Technologies Used                                             |
|---------------|---------------------------------------------------------------|
| Frontend      | [Streamlit](https://streamlit.io), Plotly, Python             |
| Backend       | Pandas, Numpy, Custom ESG + DEI Scoring Algorithms            |
| Visualization | Plotly                                                        |
| Deployment    | Streamlit Cloud                                               |
| Tools         | GitHub, VS Code                                               |

---

## 📊 Sample Features

- 🔄 Multi-file upload and auto-merging of inconsistent CSVs
- 📈 Scoring logic for DEI, Sustainability, and Performance
- 🧮 EqualChain score out of 10 (weighted)
- 📊 Interactive charts: Bar, Pie, and Geo Maps
- 🗂️ Filters: Ownership type, Packaging type, Certification, CO₂ emissions
- 📤 Export top suppliers as CSV

---

## 📂 Folder Structure

```
EqualChain/
├── app.py                        # Streamlit main dashboard app
├── scoring.py                    # Scoring logic functions
├── utils.py                      # Preprocessing + merge logic
├── /data                         # Raw & cleaned datasets
├── /assets                       # Images, thumbnails, icons
├── README.md                     # Project overview (this file)
├── requirements.txt              # Required Python packages
└── EqualChain_Merged_Cleaned_Final.csv
```

---

## 🧮 Scoring Criteria

| Metric               | Weight | Description                                    |
|----------------------|--------|------------------------------------------------|
| **DEI Score**        | 40%    | Based on Women/Minority ownership              |
| **Sustainability**   | 40%    | Based on CO₂ emissions, eco-packaging          |
| **Performance**      | 20%    | Based on certification and locality            |
| **Total Score**      | 10.0   | Combined into "EqualChain Score"               |

---

## 👨‍💻 Team Members

| Name         | Role             | Responsibility                                   |
|--------------|------------------|--------------------------------------------------|
| Pruthvinath Reddy | ML Engineer      | Score logic, dashboard integration          |
| Dhnaush           | Data Engineer    | Preprocessing, data merging, error handling |
| Mohan Krishna     | Frontend Dev     | Streamlit design, interactivity             |
| Paraser           | Analyst/Presenter| Storyboarding, pitch, and presentation prep |
