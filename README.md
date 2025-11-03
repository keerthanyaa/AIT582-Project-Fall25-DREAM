# AIT582-Metad-PROJ-Fall25
Metadata Analytics project : for the term Fall 2025. 


DREAM : Disaster Recovery and Emergency Allocation using Metadata
*using State-of-the-Art Technology for Resource Transparency*

Directory Structure:
```
AIT582-DL1/
├─ data/
│  ├─ raw/          # your JSON drops here (read-only)
│  └─ cleaned/      # cleaned CSV/Parquet outputs
├─ notebooks/
│  ├─ 01_ingest_quality.ipynb    # load + schema + missingness + save cleaned
│  ├─ 02_validate_eda.ipynb      # recreate/confirm Checkpoint-1 plots
│  └─ 03_modeling.ipynb          # H2 stats + H3 classification & tuning
├─ src/
│  └─ utils.py      # tiny helpers (load_json, parse_dates, save_df, plots)
├─ reports/
│  └─ figures/      # charts exported from notebooks
├─ .gitignore
└─ README.md

```