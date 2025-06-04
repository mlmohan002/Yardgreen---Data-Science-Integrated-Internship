# Power  BI Project Link:
https://app.powerbi.com/Redirect?action=OpenReport&appId=dde5cf6c-ae71-47c2-be59-faf1da191fba&reportObjectId=c952197d-5f58-4ac9-8012-6581577de105&ctid=3e71a923-9a43-4d6c-b58f-49294d89e08f&reportPage=2fe57f080d49307f2881&pbi_source=appShareLink&portalSessionId=e52de640-9a2d-4fd6-a8bd-49e79f305939
# Yardgreen---Data-Science-Integrated-Internship
# 🚦 Traffic Data Analysis Project

**Yardgreen - Data Science Integrated Internship**

## 📌 Overview

This project focuses on analyzing traffic data to uncover patterns and insights that could support urban planning, optimize traffic flow, and improve road safety. The dataset includes hourly vehicle counts across multiple junctions in a city.

---

## 📁 Dataset Description

| Variable     | Description                                    | Type       |
|--------------|------------------------------------------------|------------|
| `DateTime`   | Timestamp of traffic count (hourly)            | DateTime   |
| `Junction`   | ID of the junction where data was collected    | Integer    |
| `Vehicles`   | Number of vehicles detected in that hour       | Integer    |
| `ID`         | Unique identifier for the row (derived)        | Integer    |

---

## 📊 Objectives

- Time-series analysis of traffic volume
- Peak and off-peak traffic pattern identification
- Comparison of traffic loads across junctions
- Recommendations for traffic management

---

## 🔧 Tools & Technologies


- **Power BI / Power Query** for data transformation


---

## 🚀 Project Structure

```bash
.
├── data/
│   └── traffic_dataset.csv
├── notebooks/
│   └── analysis.ipynb
├── visuals/
│   └── traffic_trends.png
├── README.md
└── .gitignore
