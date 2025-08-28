 # Survey Data Visualization Project

## 🔹 Project Overview
Survey results are often under-utilized due to poor analysis and lack of visualization.
This project takes raw survey responses and transforms them into informative visual summaries using Python, Seaborn, Matplotlib, and Plotly.
The goal is to help stakeholders quickly identify trends, preferences, and insights from survey data.

## 🔹 Objectives

- Analyze survey results (demographics, preferences, satisfaction ratings).

- Create bar charts, pie charts, histograms, boxplots, and heatmaps for better understanding.

- Build interactive charts with Plotly for dynamic exploration.

- Export findings into a comprehensive PDF report with all visuals and insights.

## 🔹 Dataset
- File: `survey_data.csv`

- Size: 1000 rows (synthetic dataset generated for testing)

- Columns:

    - `ID` – Unique respondent ID

    - `Age` – Age of respondent (18–60)

    - `Gender` – Male / Female / Other

    - `Country` – Country of respondent

    - `Satisfaction` – Rating (1–5 scale)

    - `Preferred_Platform` – Chosen platform (YouTube, Instagram, etc.)

    - `Usage_Frequency` – Daily / Weekly / Monthly / Rarely

    - `Recommend` – Yes / No


## 🔹 Features
✅ Static Visualizations with Matplotlib & Seaborn

✅ Interactive Dashboards using Plotly

✅ Correlation Heatmaps for pattern discovery

✅ PDF Report Generation with all charts and insights

✅ Easy-to-run Jupyter/Colab Notebook


## 🔹 Project Structure
```bash
Survey_Visualization_Project/
│── data/
│   └── survey_data.csv          # Dataset (1000 rows)
│── notebook/
│   └── survey_analysis.ipynb    # Main analysis notebook
│── reports/
│   ├── figures/ 
│   │   ├── Correlation Heatmap.png
│   │   ├── Country wise Prefference.png
│   │   ├── Gender Distribution.png
│   │   ├── Preffered Platforms.png
│   │   ├── Satisfaction by Gender.png
│   │   ├── Satisfaction Score Dist.png
│   │   └── Usage frequency VS Satisfaction.png
│   └── survey_summary.pdf       # Final PDF report with charts
│── README.md                    # Project documentation
│── requirements.txt             # Dependencies
```

## 🔹 Installation
**1.** Clone this repository:
```bash
git clone https://github.com/Hariharan-T27/survey-analytics.git
cd Survey_Visualization_Project
```

**2.** Install dependencies:
```bash
pip install -r requirements.txt
```

**3.** Run the Jupyter Notebook or Google Colab file.

## 🔹 Usage
- Open the notebook:
```bash
jupyter notebook notebook/survey_analysis.ipynb
```

- Or upload the `.ipynb` file to Google Colab and run.

- To generate the PDF report inside Colab:
```bash
generate_full_pdf(df)

```

- To download the report in Colab:
```bash
from google.colab import files
files.download("survey_summary.pdf")
```

## 🔹 Expected Output
- Charts: Gender distribution, platform preferences, satisfaction histograms, heatmaps.

- Interactive Visuals: Drill down into responses by demographics.

- PDF Report: Consolidated document with visuals + insights.

## 🔹 Tech Stack
- Python – Data analysis

- Pandas – Data manipulation

- Matplotlib / Seaborn – Static visualizations

- Plotly – Interactive dashboards

- ReportLab – PDF generation

## 🔹 Future Improvements
- Add NLP for analyzing open-ended survey feedback.

- Build a Streamlit/Dash web dashboard for live visualization.

- Connect to real survey platforms (Google Forms, Typeform).


**Author:** Hariharan

**Date:** August 2025
