# European Weightlifting Market Analysis

A data-driven analysis of the European weightlifting market (2019–2021) designed to validate the business hypothesis for Lift & Lead, a startup evaluating the opening of specialized training centers. Developed as part of the Master’s in Data & AI — Nuclio Digital School.

## Key Features

* Data Wrangling: Loads and cleans data from the 2019 and 2021 European Weightlifting Championships.
* Reshaping: Transforms the dataset from wide to long format to streamline medalist-level analysis.
* Feature Extraction: Isolates key variables including athlete names, country, and performance metrics (Snatch, Clean & Jerk, and Total).
* Competitive Landscape: Analyzes medal distribution by country and gender to identify market hotspots.
* Hypothesis Validation: Uses real competition data to assess the growth and viability of the sport for business expansion.

## Project Structure

```
european-weightlifting-analysis/
├── data/
│   ├── halterofilia_2019.csv
│   ├── halterofilia_2020.csv
│   ├── halterofilia_2022.csv
│   ├── halterofilia_2023.csv
│   └── halterofilia_2024.csv
├── weightlifting_analysis.ipynb     # Pipeline completo de análisis
├── Lift_and_Lead.pptx               # Presentación PPT
└── README.md
```

## Installation & Usage
```bash
pip install pandas numpy matplotlib seaborn plotly missingno fuzzywuzzy jupyter
jupyter notebook weightlifting_analysis.ipynb
```

## Analysis Context

Please note that data labeled 2020 actually refers to the 2021 championships, as the 2020 event was cancelled due to the COVID-19 pandemic.

## Tech Stack

Python (Pandas, Numpy, Matplotlib, Seaborn, Plotly, Missingno, Fuzzywuzzy) · Jupyter Notebook
