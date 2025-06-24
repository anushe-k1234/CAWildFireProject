# CAWildFireProject
Data Science/Analytics Project Using CA Wildfire Data

## Overview
This project analyzes historical wildfire data in California to understand trends, explore relationships with climate and human factors, and build predictive models. It combines exploratory analysis, geospatial visualization, and machine learning to answer the primary question:

> **How have wildfire patterns and impacts in California changed over time, and what factors best predict their severity and outcomes?**

---

## Project Structure

CAWildFireProject/

- 01_data_preparation.ipynb # Data loading, cleaning, merging
- 02_eda_visuals.ipynb # Visual exploratory analysis and mapping
- 03_modeling_predictions.ipynb # Regression and classification models
- 04_results_report.ipynb # Final summary, key findings, limitations

data/ # Raw and processed datasets
- CAWeatherFirePrediction.csv
- CAFireParameter.csv.csv
- countyRisk.csv
- dataset1_cleaned.csv
- dataset2_cleaned.csv
- dataset3_cleaned.csv

Additional Files
- models/ # Saved models and SHAP values
- figures/ # Generated plots and visualizations
- README.md # Project overview and usage
- requirements.txt # Python package dependencies

---

## Data Sources

- **df1:** Daily weather and fire metrics (from NOAA and Cal Fire)
- **df2:** Fire perimeter shapefiles + metadata (Cal Fire perimeter dataset)
- **df3:** FEMA Risk Index and county-level socioeconomic data

---

## Key Analyses

- Trends in fire size, frequency, and duration by season/year
- Climate–fire correlations using regression
- Geospatial mapping of hotspots
- Predictive models:
  - Fire size (regression)
  - Mega fires (binary classification)
  - Damage cost (regression)

---

## Modeling Techniques

- **Random Forests**, **XGBoost**, and **Linear Regression**
- **SHAP** for feature importance and model interpretation
- **Classification metrics**: ROC, precision, recall, F1
