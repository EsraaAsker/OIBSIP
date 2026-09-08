# OIBSIP Data Science Demo — Laptop Run Guide

## 1. Install Python
Install Python 3.10+ and make sure `python` and `pip` work in Terminal/PowerShell.

## 2. Create an environment

### Windows PowerShell
```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

### macOS/Linux
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## 3. Launch Jupyter
```bash
jupyter notebook
```
Open one notebook at a time and use **Kernel → Restart & Run All**.

## Demo order
1. `DataScience-L1-IrisClassification` — fastest classification demo.
2. `DataScience-L1-SalesPrediction` — regression and channel-impact charts.
3. `DataScience-L1-SpamDetection` — NLP/TF-IDF and confusion matrices.
4. `DataScience-L1-UnemploymentAnalysis` — time series and regional EDA.
5. `DataScience-L1-CarPricePrediction` — cleaning, encoding, and regression.

## Recording tips
Start with the README/objective, show the dataset shape and null check, run the visualizations, then show the model metrics and final recommendation. Keep each video 60–120 seconds and record the notebook output, not the installation logs.

The two external-data projects include small public CSV files in their `data/` folders, so the first demo run does not require a separate download.
