# DAT490 — Yelp Arizona + ACS

This repository contains the full code appendix (notebooks) and generated figures for our DAT490 project analyzing Yelp Arizona businesses and ZIP-level neighborhood context from the American Community Survey (ACS).

## Code Appendix 
All code is included as Jupyter notebooks in:
- **`notebooks/`**

### Notebook order 
1. `notebooks/az_data_clean.ipynb`  
   Cleans Yelp AZ businesses and produces analysis-ready variables.
2. `notebooks/getACS.ipynb`  
   Pulls ACS 2023 5-year ZIP/ZCTA variables via the Census API and prepares the ZIP table.
3. `notebooks/EDA.ipynb`  
   Generates exploratory plots and saves them into `figs/`.
4. `notebooks/METH.ipynb`  
   Builds predictive models, evaluates performance, and produces modeling figures.

## Figures
All figures referenced in the report are stored in:
- **`figs/`** (including `figs/meth/` for modeling/EDA panels)

## Data note
Raw datasets are not committed. If you want to reproduce results, download the Yelp Open Dataset and set local paths inside the notebooks, and provide a Census API key if required.

## Links
- Repo: https://github.com/ZihaoPeng35/dat490-yelp-az-acs
