 # BEMM457 Individual Project – London Cycle Hire Analytics

This repository contains my individual coursework project for BEMM457.  
The project uses a Kaggle subset of Transport for London (TfL) cycle hire data (August 2023) to analyse hourly hire demand and draw implications for a future shared bicycle and e-scooter scheme in Exeter.

---

## Repository contents

- `notebooks/`
  - `01_cleaning_and_eda.ipynb` – data loading, cleaning, descriptive statistics and exploratory plots.
  - `02_modelling.ipynb` – regression models (hour and weekend effects), model evaluation and diagnostic plots.
- `data_processed/`
  - `hourly_counts_2023_sample.csv` – aggregated hourly hire counts used for the analysis.
- `data_raw/`
  - Local folder for the original Kaggle CSV file. This is **not tracked in Git** (see `.gitignore`) because it is large and derived from open data.
- `figures/`
  - PNG images exported from the notebooks and used in the written report (e.g. daily/hourly demand plots, regression diagnostics).
- `requirements.txt`
  - List of Python packages used in the notebooks.

---

## How to run the analysis

1. Install the required Python packages:

   ```bash
   pip install -r requirements.txt


