https://app.powerbi.com/links/74GcWotWAb?ctid=3e71a923-9a43-4d6c-b58f-49294d89e08f&pbi_source=linkShare
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
