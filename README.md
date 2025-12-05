# DAT490 Yelp Arizona + ACS

This repo contains the full analysis code used in the project report.

## What’s included
- `notebooks/az_data_clean.ipynb`: Yelp AZ filtering, cleaning, feature engineering
- `notebooks/getACS.ipynb`: ACS ZIP-level covariates via Census API
- `notebooks/EDA.ipynb`: exploratory analysis + plots saved to `figs/`
- `notebooks/METH.ipynb`: modeling, evaluation, and feature plots
- `figs/`: figures used in the report

## Notes
Raw Yelp data is not included due to size/licensing. Notebooks assume you provide the Yelp dataset locally.
If an ACS API key is needed, store it as an environment variable instead of hard-coding it.