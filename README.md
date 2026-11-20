# Customer360 Lite: Customer Analytics and Churn Prediction

> **Status:** work in progress. Sections marked _TBD_ are filled in only after the analysis has been run on the real data.

## Objective
Analyze e-commerce customer behavior, segment customers with RFM + K-Means, predict customer inactivity, and turn the results into business recommendations for marketing and commercial BI teams.

## Dataset
[Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) (Kaggle). The data is not included in this repository. Download it and place the CSV files in `data/raw/`.

## Project structure
```
data/raw/        original Kaggle CSVs (not tracked)
data/processed/  derived tables (not tracked)
notebooks/       00 inspection, 01 EDA, 02 RFM segmentation, 03 churn prediction
src/             reusable loading and feature code
app/             Streamlit dashboard
reports/figures/ saved charts
models/          saved models (not tracked)
```

## Methodology
_TBD: filled in as each phase is completed._

## Results
_TBD: all numbers will be copied from actual notebook outputs._

## Limitations
_TBD._

## How to run
```bash
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\Activate.ps1
pip install -r requirements.txt
# put the Olist CSVs in data/raw/
jupyter notebook                 # run notebooks in order
streamlit run app/streamlit_app.py
```
