 # BEMM457 – Individual Analytics Project  
**Topic:** Bicycle-hire demand patterns using London Cycle Hire (August 2023)  
**Student:** [Your name / ID]

This repository contains all code and supporting files for my BEMM457 individual assignment.  
The project analyses hourly bicycle-hire demand using a Kaggle subset of Transport for London (TfL) cycle-hire data to inform planning for Exeter City Council’s proposed shared bicycle and e-scooter scheme.

---

## Repository structure

```text
.
├── notebooks/
│   ├── 01_cleaning_and_eda.ipynb     # Data loading, cleaning, and exploratory analysis
│   └── 02_modelling.ipynb            # Regression models, diagnostics, and key figures
├── data_raw/                         # Local raw data (excluded from Git, see .gitignore)
├── data_processed/
│   └── hourly_counts_2023_sample.csv # Aggregated hourly hire counts used for modelling
├── figures/                          # Exported charts used in the report (PNG)
├── requirements.txt                  # Python package dependencies
└── .gitignore                        # Ensures large raw data are not committed

