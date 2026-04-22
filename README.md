# QMProject

This repository contains the notebook `Fixed_Derivatives_Project_enhanced (2).ipynb`.
All required datasets are pre-downloaded in the `data/` folder, so the notebook runs without API or database calls.

## Setup

Create and activate a virtual environment:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Install required libraries:

```bash
pip install -r requirements.txt
```

## Run

Start Jupyter and open the notebook:

```bash
jupyter lab
```

## Offline Data

The repository already includes:

- `data/calib_data.pkl`
- `data/full_data.pkl`
- `data/iv_surface.pkl`
- `data/risk_free_rate.json`

The notebook is configured in submission mode (`SUBMISSION_MODE = True`) and loads these local files by default. If any file is missing, it raises a clear error instead of trying to download live data.
