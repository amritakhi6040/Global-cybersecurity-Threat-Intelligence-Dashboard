# 🛡️ Global Cybersecurity Threat Intelligence Dashboard

> An interactive Power BI dashboard analyzing global cybersecurity incidents from **2015 to 2024** — transforming raw threat data into actionable intelligence.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Objectives](#objectives)
- [Tools & Technologies](#tools--technologies)
- [Dataset Description](#dataset-description)
- [Dashboard Features](#dashboard-features)
- [Key Insights](#key-insights)
- [Learning Outcomes](#learning-outcomes)
- [Future Improvements](#future-improvements)
- [References](#references)
- [Acknowledgements](#acknowledgements)
- [Author](#author)

---

## Overview

Cybersecurity threats are evolving at an unprecedented pace, making it critical for organizations to understand attack patterns, vulnerable industries, and financial consequences. This project presents a **Global Cybersecurity Threat Intelligence Dashboard** built with **Power BI**, designed to visualize and explore cybersecurity incident data collected over a decade (2015–2024).

The dashboard enables analysts, researchers, and decision-makers to:
- Monitor global attack trends over time
- Identify which industries and countries are most at risk
- Assess the financial damage caused by different attack types

---

## Objectives

| # | Objective |
|---|-----------|
| 1 | Analyze global cybersecurity attack trends across multiple years |
| 2 | Identify the industries most frequently targeted by cyber threats |
| 3 | Examine financial losses caused by different categories of cyber attacks |
| 4 | Visualize the geographic distribution of incidents worldwide |
| 5 | Understand the scale of impact in terms of affected users |
| 6 | Deliver an interactive, filterable dashboard for dynamic exploration |

---

## Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Power BI** | Data visualization and dashboard development |
| **Global Cybersecurity Threats Dataset (2015–2024)** | Primary data source |
| **DAX & Power Query** | Data transformation, aggregation, and filtering |

---

## Dataset Description

The dataset captures cybersecurity threat records spanning 10 years across multiple countries and industries.

**Key attributes include:**

- `Year` — Year the incident occurred
- `Country` — Nation affected by the attack
- `Target Industry` — Sector that was targeted (e.g., Finance, Healthcare, Technology)
- `Attack Type` — Classification of the cyber threat (e.g., Ransomware, Phishing, DDoS)
- `Financial Loss (USD Million)` — Estimated monetary damage
- `Affected Users` — Number of individuals impacted
- `Incident Resolution Time` — Time taken to resolve the incident

---

## Dashboard Features

The dashboard is organized across **two pages**, each focusing on a different analytical perspective.

### 📊 Page 1 — Cyber Attack Analytics

| Visualization | Description |
|--------------|-------------|
| **Financial Loss Trend by Year** | Line/bar chart showing how total losses evolved over 2015–2024 |
| **Affected Users by Industry** | Highlights which sectors suffered the greatest user impact |
| **Cyber Attack Type Distribution** | Breakdown of attack frequency by category |
| **Financial Loss by Attack Type** | Compares economic damage across different threat vectors |
| **Avg. Resolution Time by Industry** | Reveals which sectors respond fastest or slowest to incidents |

### 🌍 Page 2 — Global Cyber Threat Overview

| Visualization | Description |
|--------------|-------------|
| **Global Cyber Attack Map** | World map showing the geographic spread of incidents |
| **Financial Loss by Country** | Comparative bar chart of economic impact by nation |
| **Attack Type Distribution by Country** | Breaks down threat categories per country |

### 🔧 Interactive Controls

- **Year Slicer** — Filter all visuals dynamically by year range
- **Cross-filtering** — Click any chart element to drill into related visuals across the page

---

## Key Insights

- 📈 **Rising Threat Volume** — Cyber attacks have increased significantly in both frequency and financial impact over the decade.
- 🏥 **High-Risk Industries** — Finance, Healthcare, and Technology consistently rank among the most targeted sectors.
- 🌐 **Geographic Disparity** — Financial losses vary widely across countries, with certain nations disproportionately affected.
- ⚖️ **Attack Type vs. Damage** — Some attack types are frequent but low-impact, while others (e.g., ransomware) cause severe economic damage despite lower occurrence rates.
- 🕐 **Resolution Gaps** — Incident resolution time differs notably by industry, suggesting varying levels of cybersecurity maturity.

---

## Learning Outcomes

Through this project, the following skills and competencies were developed:

- Designing multi-page interactive dashboards in Power BI
- Transforming and modeling raw cybersecurity datasets using Power Query and DAX
- Applying data storytelling principles to communicate complex security trends visually
- Analyzing real-world threat intelligence data for pattern discovery
- Building user-friendly dashboards with slicers, drill-throughs, and cross-filtering

---

## Future Improvements

| Enhancement | Description |
|-------------|-------------|
| **Real-Time Data Integration** | Connect to live threat intelligence feeds for up-to-date monitoring |
| **Predictive Analytics** | Incorporate machine learning models to forecast attack trends |
| **Cloud Deployment** | Publish to Power BI Service for web-based access and sharing |
| **Automated Alerts** | Set up data-driven alerts for high-risk threat thresholds |
| **Drill-Through Reports** | Enable deeper exploration at the country and industry level |

---

## References

- 📂 [Global Cybersecurity Threats Dataset — Kaggle](https://www.kaggle.com)
- 📘 [Microsoft Power BI Documentation](https://docs.microsoft.com/en-us/power-bi/)
- 📖 Data Visualization Best Practices — Microsoft & Tableau Guidelines

---

## Acknowledgements

This project was completed as part of the **Microsoft Elevate AICTE 4-Week Internship Program**.

Special thanks to **Vignesh Muthuvelan** for guidance and mentorship throughout the project.

---

## Author

**[Amritakhi Mohapatra]**
B.Tech Computer Science Student
Data Analytics & AI Enthusiast



---

*© 2024 | Built with Power BI as part of the Microsoft Elevate AICTE Internship Program*
