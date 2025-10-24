# Bus Passenger Demand Forecasting Using Myki Card Data (SARIMA)

This repository contains the complete workflow for the study **Hourly Bus Passenger Demand Forecasting Using SARIMA**. The project explores Seasonal Autoregressive Integrated Moving Average (SARIMA) models to forecast hourly bus passenger demand in Melbourne using aggregated Myki smart-card data provided by the Victorian Department of Transport.

> **Data sharing**: Due to data-sharing restrictions, the original Myki dataset **cannot be publicly released**. All analysis code, model configuration, and figure-generation scripts are provided to ensure methodological transparency and reproducibility.

## Contents
- `notebooks/Typical_Weekday_SARIMA_v6.ipynb` – end-to-end pipeline: frame construction, SARIMA fitting, validation, and heatmap generation  
- `requirements.txt` / `environment.yml` – Python dependencies  
- `output/` – folders where figures and frames are saved by the notebook

## Quickstart

**Option A – pip**
```bash
python -m venv .venv && source .venv/bin/activate   # (Windows: .venv\Scripts\activate)
pip install -r requirements.txt
jupyter notebook notebooks/Typical_Weekday_SARIMA_v6.ipynb
