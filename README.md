# European Weightlifting Market Analysis

Un análisis de datos del mercado europeo de halterofilia (2019–2021) para validar la hipótesis de negocio de Lift & Lead, una startup que evalúa abrir centros especializados en este deporte. Proyecto del Máster en Data & AI — Nuclio Digital School.

## qué hace

* carga y limpia datos de los campeonatos europeos de halterofilia de 2019 y 2021
* transforma el dataset de formato ancho a largo para facilitar el análisis por medallista
* extrae nombre, apellido, país y resultados (arrancada, dos tiempos, total) de cada atleta
* analiza la distribución de medallas por país y género
* valida hipótesis de crecimiento del deporte con datos reales de competición

## estructura

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

## cómo ejecutarlo

```bash
pip install pandas numpy matplotlib seaborn plotly missingno fuzzywuzzy jupyter
jupyter notebook weightlifting_analysis.ipynb
```

## contexto del análisis

los datos de 2020 corresponden realmente a 2021 porque el campeonato de 2020 fue cancelado por la pandemia de COVID-19.

## stack

python · pandas · numpy · matplotlib · seaborn · plotly · missingno · fuzzywuzzy
