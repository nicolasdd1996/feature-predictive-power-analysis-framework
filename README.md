# Feature Predictive Power (FPP)

A lightweight framework for analyzing the **predictive power** of features/signals over a target variable (regression or binary classification).  

It includes:

- Fast **quality checks** (NaN fraction, ADF stationarity test, Spearman correlations)  
- Predictive power metrics: **IC** (Spearman Information Coefficient) and **MI** (Mutual Information)  
- **Randomization tests** (shuffled targets) with |IC| and MI **z-scores**  
- Composite power ranking and compact visualization panels  
- **Decile/quintile feature support** for intuitive bar plots  

> Designed for quant research and early-stage feature validation.

---

## Installation

Python ≥ 3.10 recommended.

```bash
pip install -r requirements.txt
# or, using conda:
# conda env create -f environment.yml && conda activate fpp
