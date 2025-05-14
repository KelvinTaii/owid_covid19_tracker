# 🌍 COVID-19 Global Data Tracker

A data analysis project that tracks and visualizes global COVID-19 trends using real-world data. This project focuses on exploring time-based trends in cases, deaths, and vaccinations across selected countries, providing key insights through data visualizations and narrative reporting.

## 📊 Project Overview

This Jupyter Notebook-based project uses global COVID-19 data to:

- Analyze time-series trends for confirmed cases, deaths, and vaccinations.
- Compare metrics across selected countries (e.g., Kenya, India, United States).
- Visualize insights with line charts, bar graphs, and optional choropleth maps.
- Present a clear and structured data report suitable for publishing or presentation.

## 📁 Project Structure

```
covid19-global-tracker/
│
├── data/
│   └── owid-covid-data.csv               # COVID-19 dataset from Our World in Data
│
├── notebooks/
│   └── covid19_analysis.ipynb            # Main analysis notebook
│
├── visuals/
│   └── *.png, *.jpg                      # (Optional) Saved visual outputs
│
├── report/
│   └── covid19_report.pdf                # (Optional) Final exported report
│
├── README.md                             # Project overview and instructions
└── requirements.txt                      # Python dependencies
```

## 🚀 How to Run

1. Clone this repository or download the files.
2. Make sure you have Python 3.7+ installed.
3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Open the Jupyter Notebook:

```bash
jupyter notebook notebooks/covid19_analysis.ipynb
```

5. Run the notebook cells to load data, analyze trends, and visualize insights.

## 📦 Data Source

Data used in this project comes from:

- [Our World in Data – COVID-19 Dataset](https://ourworldindata.org/coronavirus-source-data)

## 🧪 Tools & Libraries

- Python
- pandas
- matplotlib
- seaborn
- plotly (optional)
- Jupyter Notebook

## 📈 Key Features

- Load and clean real-world COVID-19 data
- Filter and compare countries of interest
- Plot total cases, deaths, and vaccinations over time
- Calculate death rates and vaccination coverage
- Generate meaningful visualizations to support findings
- Optional: Create interactive choropleth maps

## 📝 Insights

The notebook includes several narrative insights such as:

- Country comparisons on cases and vaccinations
- Death rate trends
- Observations of global pandemic waves

## ✅ Final Deliverable

A well-documented Jupyter Notebook that:

- Loads and processes COVID-19 data
- Visualizes trends and statistics
- Communicates key findings with narrative explanations

---

> 📌 This project was developed as part of a data analysis assignment to apply real-world data wrangling, visualization, and reporting skills.
