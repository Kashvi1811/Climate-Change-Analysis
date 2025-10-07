# Climate Change Analysis & Dashboard 🌍
Exploratory Data Analysis of global climate indicators to uncover trends, correlations, and forecasting foundations for policy-relevant insights.

## 📑 Table of Contents
- [Overview](#-overview)
- [Features](#-features)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Usage](#-usage)
- [Tech Stack](#-tech-stack)
- [Future Improvements](#-future-improvements)
- [License](#-license)
- [Contact](#-contact)

## 🔎 Overview
This project analyzes multi-factor climate datasets to understand global environmental change and its drivers. Using Exploratory Data Analysis (EDA), the study highlights key insights across temperature rise, CO₂ emissions, sea levels, renewable adoption, forest area stability, and extreme weather events.

The repository provides:
- A reproducible workflow for climate EDA (cleaning, trends, correlations, projections).
- An **interactive Tableau dashboard** for dynamic climate KPIs.
- Statistical foundations for **10-year forward projections**.

🔗 **Live Dashboard:** [View on Tableau](https://prod-in-a.online.tableau.com/t/climate_change_analysis_dashboard/views/Climate_Change_Analysis/Dashboard1)  
📂 **Dataset:** [Kaggle – Climate Change Dataset](https://www.kaggle.com/datasets/bhadramohit/climate-change-dataset)

## ✨ Features

- **Trend Analysis:** Track global warming, emissions, and extreme weather events.
- **Correlation Matrix:** Explore interdependencies between population, emissions, and ecosystems.
- **Variability Studies:** Compare renewable energy adoption and forest stability across regions.
- **Forecasting Prep:** Linear regression baseline for 10-year projections.
- **Interactive Dashboard:** Multi-panel Tableau dashboard with KPIs & visuals.

## 📂 Project Structure
climate-change-analysis/
├── climate-change-analysis.ipynb   # Full EDA notebook  
├── climate_change_dataset.csv      # Source dataset  
├── Climate_Change_Analysis.twbx    # Tableau packaged dashboard
├── dashboard_image.png                       # Dashboard snapshot  
└── README.md                       # Project documentation  

## ⚡ Getting Started
1. Clone the repository:
```bash
git clone https://github.com/<your-username>/credit-risk-eda.git
cd credit-risk-eda
````

2. (Optional) Create a virtual environment:

```bash
python -m venv env
source env/bin/activate       # macOS / Linux
env\Scripts\activate          # Windows PowerShell
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```
## 🖥️ Usage

- Open the Jupyter Notebook:
jupyter notebook climate-change-analysis.ipynb


- Run the notebook step by step to explore:
- 🧹 **Data cleaning & preprocessing**  
- 📈 **Trend & correlation analysis**  
- 📊 **Variability & outlier checks**  
- 🔮 **Projection setup (10-year forward)**  

Open the Tableau workbook (`Climate_Change_Analysis.twbx`) for interactive insights.

---

## 🛠 Tech Stack

- 🐍 Python, Jupyter  
- 📦 pandas, NumPy  
- 📊 Matplotlib, Seaborn, SciPy  
- 🖼 Tableau (interactive dashboarding)  

---

## 🚀 Future Improvements

- 📉 Add **time-series forecasting** (ARIMA, Prophet, ETS).  
- 🗺️ Integrate **geospatial analysis** (choropleth maps).  
- 💹 Add **carbon intensity per GDP** metric.  
- 🔄 Extend dashboard with **scenario toggles** (baseline vs intervention).  

---

## 📜 License

This project is intended for educational and personal use. All rights reserved by **Kashvi1811**.  
*For any usage beyond personal or educational purposes, please contact me in advance.*

## 🤝 Contact & Colloboration

I’m always open to feedback, ideas, and collaboration opportunities! Feel free to reach out:

- **GitHub:** [@Kashvi1811](https://github.com/Kashvi1811)
- **LinkedIn:** https://www.linkedin.com/in/kashvi-soni-6330a92b2/
- **Email:** kashvisoni2005@gmail.com

