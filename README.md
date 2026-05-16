# ONCF Passenger Satisfaction Dashboard 2026

[![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Google Colab](https://img.shields.io/badge/Open%20in-Colab-F9AB00?logo=googlecolab&logoColor=white)](https://colab.research.google.com/github/[USERNAME]/[REPO]/blob/main/notebooks/ONCF_Dashboard.ipynb)
[![Plotly](https://img.shields.io/badge/Plotly-Interactive-3F4F75?logo=plotly&logoColor=white)](https://plotly.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Made with Love](https://img.shields.io/badge/Made%20with-❤-red.svg)]()

**An interactive dashboard to analyze passenger satisfaction for ONCF (Moroccan Railways).**

Built with Python in Google Colab, the dashboard combines real survey responses from Google Sheets with AI‑generated synthetic data (100 total responses) and presents findings through dynamic Plotly visualizations.

---

## Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Project Structure](#-project-structure)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Dashboard Preview](#-dashboard-preview)
- [Data & Methodology](#-data--methodology)
- [Key Insights](#-key-insights)
- [Live Demo](#-live-demo)
- [Contributing](#-contributing)
- [License](#-license)

---

##  Overview

This project delivers a **standalone, interactive HTML dashboard** for ONCF, providing a 360° view of customer satisfaction from **January 3 to May 9, 2026**.

- **Real data**: 10 original survey entries loaded directly from a Google Sheet.
- **Synthetic enrichment**: 90 additional responses generated with realistic rules (reproducible, seed=42).
- **Visual story**: 6 interactive Plotly charts, KPI cards, and a detailed summary table.
- **Fully portable**: The final dashboard is a single `.html` file – no server needed.

---

##  Features

-  **Google Sheets Integration** – One‑click data import from your existing survey sheet.
-  **Synthetic Data Generation** – 90 realistic passenger profiles with logical correlations (satisfaction, problems, delays).
-  **Interactive Visualizations** – Zoom, hover, and explore every chart.
-  **4 KPI Cards** – Overall satisfaction, recommendation rate, delay rate, total respondents.
-  **Time‑series analysis** – Monthly evolution of satisfaction.
-  **Breakdown by train type & route** – Compare TGV, Al Atlas, TNR, and Navette.
-  **Responsive Design** – Works on desktop, tablet, and mobile.
- 🎨 **ONCF‑themed UI** – Clean red‑and‑white colour palette.

---

## 🗂 Project Structure
-ONCF-Satisfaction-Dashboard/

-│
-├── README.md 
-├── LICENSE 
├── requirements.txt 
├── .gitignore
│
├── notebooks/
│ └── ONCF_Dashboard.ipynb 
│
├── src/
│ ├── data_generator.py 
│ └── dashboard_builder.py 
│
├── data/
│ └── original_responses.csv 
│
├── assets/
│ └── screenshots/
│ ├── dashboard_full.png
│ ├──
kpi_cards.png
│ └── radar_chart.png
│
└── ONCF_Dashboard.html

---

## 🔧 Tech Stack

| Component          | Technology                        |
|--------------------|-----------------------------------|
| **Environment**    | Google Colab                      |
| **Data Source**    | Google Sheets (via `gspread`)     |
| **Data Manipulation** | Pandas, NumPy                   |
| **Visualization**  | Plotly (interactive charts)       |
| **Synthetic Data** | Faker + custom rule engine        |
| **Export**         | Standalone HTML with Plotly.js    |
| **Version Control**| Git & GitHub                      |

---
### Resultat
<div>
   <img width="1350" height="480" alt="Image" src="https://github.com/user-attachments/assets/995a09ec-347e-4bf7-8a81-29a561440ab4" />
   <img width="1339" height="431" alt="Image" src="https://github.com/user-attachments/assets/bf73be51-4426-421b-8347-13a48daafbf5" />
   <img width="656" height="449" alt="Image" src="https://github.com/user-attachments/assets/f43ac668-562f-4a29-8a59-086b626ba54b" />
   <img width="653" height="445" alt="Image" src="https://github.com/user-attachments/assets/6ea0ddee-33d7-4099-97f4-ac06415b5e27" />
</div>


### Prerequisites

- A Google account (for Colab and Sheets)
- A Google Sheet with the survey columns (see [Data Format](#-data--methodology))
- Basic knowledge of running a Colab notebook


   
