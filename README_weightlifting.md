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
├── weightlifting_analysis.ipynb   # pipeline completo: limpieza, EDA, hipótesis
└── README.md
```

## cómo ejecutarlo

```bash
pip install pandas numpy matplotlib seaborn plotly missingno fuzzywuzzy jupyter
jupyter notebook weightlifting_analysis.ipynb
```

los datos originales son CSVs scrapeados de Wikipedia con resultados de los campeonatos europeos. actualiza las rutas en la celda de carga de datos.

## contexto del análisis

los datos de 2020 corresponden realmente a 2021 porque el campeonato de 2020 fue cancelado por la pandemia de COVID-19.

## stack

python · pandas · numpy · matplotlib · seaborn · plotly · missingno · fuzzywuzzy
