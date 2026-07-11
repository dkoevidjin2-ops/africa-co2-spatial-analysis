# africa-co2-spatial-analysis
Spatial analysis and prediction of CO₂ emissions in Africa using Python, GIS and Machine Learning.
# 🌍 Spatial Analysis and Prediction of CO₂ Emissions in Africa

[![Python](https://img.shields.io/badge/Python-3.11-blue.svg)]()
[![GeoPandas](https://img.shields.io/badge/GeoPandas-GIS-green.svg)]()
[![Machine Learning](https://img.shields.io/badge/Machine%20Learning-XGBoost-orange.svg)]()
[![License](https://img.shields.io/badge/License-MIT-red.svg)]()

## Overview

This project presents an end-to-end geospatial data science workflow for analysing and predicting CO₂ emissions across Africa using the EDGAR 2025 database.

The study integrates Geographic Information Systems (GIS), spatial statistics and machine learning to identify emission hotspots and forecast future emission patterns.

The project was developed to support evidence-based climate policy and sustainable development planning.

---

## Objectives

- Analyse spatial distribution of CO₂ emissions.
- Detect statistically significant emission clusters.
- Identify hotspot and coldspot regions.
- Develop predictive models for future emissions.
- Build interactive dashboards for decision-makers.

---

## Dataset

Source:

EDGAR 2025

Variables include

- CO₂ emissions
- Country
- Coordinates
- Industrial sectors
- Population
- GDP
- Energy indicators

---

## Technologies

Python

GeoPandas

Pandas

NumPy

Scikit-Learn

XGBoost

LightGBM

CatBoost

PySAL

Folium

Plotly

Matplotlib

Power BI

---

## Workflow

Raw Data

↓

Cleaning

↓

Feature Engineering

↓

Spatial Analysis

↓

Spatial Autocorrelation

↓

Hotspot Detection

↓

Machine Learning

↓

Prediction Maps

↓

Interactive Dashboard

---

## Spatial Analysis

The project performs:

✔ Global Moran's I

✔ Local Moran (LISA)

✔ Getis-Ord Gi*

✔ Spatial Weights Matrix

✔ Spatial Clustering

---

## Machine Learning Models

Three algorithms were evaluated.

- XGBoost
- LightGBM
- CatBoost

Performance metrics

- RMSE
- MAE
- R²

---

## Results

The project successfully identifies:

- Major African emission hotspots

- Spatial clusters

- Regional disparities

- Future emission trends

---

## Repository Structure

```text
data/
notebooks/
src/
figures/
maps/
models/
outputs/
```

---

## Dashboard

The interactive dashboard allows users to

- Explore emissions by country

- Visualize hotspots

- Compare regions

- Analyse temporal evolution

---

## Example Maps

(Add screenshots)

---

## Installation

```bash
git clone https://github.com/yourname/africa-co2-spatial-analysis.git

cd africa-co2-spatial-analysis

pip install -r requirements.txt
```

---

## Author

Solagnon Edoh KOEVIDJIN

Data Scientist | GIS Analyst | Climate Researcher
