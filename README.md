# Polar Sport Analytics

**Applied Sport Science Monitoring: A 7-year longitudinal case study of a multisport athlete during international transition.**

## Overview

This project analyzes ~7 years of personal training, recovery, and sleep data collected via Polar wearable devices (2019–2026). It applies sport science methodologies to quantify training load, recovery status, and physiological adaptation in a single-case longitudinal design.

## Dataset

- **1,089** training sessions across 10+ sport modalities
- **1,689** total training hours
- **1,300+** nights of continuous HR and HRV monitoring
- **21** fitness tests (Polar OwnIndex / VO2max estimation)
- **84** months of resting HR tracking

## Project Structure

```
polar-sport-analytics/
├── data/
│   ├── raw/              # Original Polar JSON export (not shared)
│   └── processed/        # Clean CSV/parquet files
├── notebooks/
│   ├── 01_etl_pipeline.ipynb
│   ├── 02_exploratory_analysis.ipynb
│   └── ...
├── src/                  # Reusable Python modules
├── requirements.txt
└── README.md
```

## Planned Analyses

1. **Descriptive training history** — volume, distribution, sport breakdown
2. **Training polarization (80/20)** — time-in-zone vs Seiler's model
3. **ACWR & Foster's monotony** — load monitoring and injury risk
4. **HR drift & threshold estimation** — submaximal cardiac drift analysis
5. **International relocation experiment** — interrupted time series (Colombia → NZ)
6. **Daily readiness system** — HRV-based composite score
7. **Banister fitness-fatigue model** — performance modeling with impulse-response

## Tech Stack

Python · pandas · NumPy · Plotly · SciPy · Jupyter · Streamlit

## Author

Nicolás — Performance Consultant | Christchurch, New Zealand

## License

This project is shared for educational and portfolio purposes. Raw data is not included for privacy reasons.
