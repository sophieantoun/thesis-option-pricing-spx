# SPX Option Pricing Models — Master Thesis

**Institution:** Université Paris Dauphine — PSL, MS 203 Financial Markets  
**Author:** Sophie-Claire ANTOUN  
**Advisor:** Prof. Aymeric Kalife  
**Date:** June 2026

---

## Research Question

*Do option prices reveal the tail risk embedded in financial markets?*

This thesis calibrates Black-Scholes, Merton Jump-Diffusion and Variance Gamma 
on Bloomberg SPX option data collected on 8 June 2026, and compares their ability 
to capture downside tail risk.

---

## Notebooks

- `data_collection.ipynb` — data loading and cleaning from Bloomberg OMON
- `models_bloomberg_clean.ipynb` — calibration, Monte Carlo simulation, tail risk measures

---

## Data

Option data are proprietary (Bloomberg) and not included in this repository.  
Spot price history is downloaded automatically via `yfinance`.

---

## Requirements

```bash
pip install numpy pandas matplotlib scipy openpyxl yfinance
```
