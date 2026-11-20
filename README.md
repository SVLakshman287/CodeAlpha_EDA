# CodeAlpha_EDA — Exploratory Data Analysis on Scraped Books Dataset

## 📌 Project Overview
This project performs comprehensive **Exploratory Data Analysis (EDA)** on the 1,000-record dataset collected in Task 1 (`books_data.csv`). Using statistical summaries, frequency distributions, and hypothesis testing, the script uncovers pricing patterns, rating distributions, inventory status, and duplicate anomalies.

## 🛠️ Technologies Used
- **Python 3.14**
- **CSV & Statistics (Built-in):** Data ingestion, mean/median/standard deviation calculations, and grouped aggregations.
- **Collections (`Counter`, `defaultdict`):** Categorical frequency analysis and multi-tier grouping.
- **HTML/CSS Visual Reporting:** Automated generation of visual distribution bar charts (`outputs/eda_charts.html`).

## 📂 Folder Structure
```text
CodeAlpha_EDA/
├── data/
│   └── books_data.csv       # Input dataset (1,000 records)
├── outputs/
│   ├── eda_summary.txt      # Full statistical EDA report
│   └── eda_charts.html      # Visual bar charts for price & ratings
├── eda_analysis.py          # Main EDA script
└── README.md                # Project documentation