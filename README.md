# Regime-Switching Time Series Modeling.
**Stochastic Modeling**  

Advanced analysis of financial time series using **Markov Regime-Switching Models** across the pre-COVID, COVID-19 pandemic, and post-pandemic recovery periods (2019–2022).

---

## Project Highlights

- Multi-asset class time series collection (equities, rates, credits, crypto, etc.)
- Visual identification of market regimes
- Markov Regime-Switching model estimation under various assumptions:
  - Different number of states
  - Constant vs regime-dependent mean (μ)
  - Constant vs regime-dependent variance (σ)
  - Full regime-dependent mean and variance
- Autoregressive regime-switching models
- Model comparison using information criteria (AIC, BIC/Schwarz, etc.)

---

## Key Tasks Completed

### Issue 1: Data Collection
- Individual collection of financial time series (2019–2022)
- Multiple asset classes represented

### Issue 2: Regime Visualization & Model Selection
- Graphs highlighting regime changes (especially around COVID)
- Group selection of primary series for modeling

### Issue 3: Model Performance Comparison
- Individual evaluation using likelihood-based information criteria
- Overall ranking of models

### Issue 4: Advanced Autoregressive Regime-Switching
- Models with regime-dependent AR coefficients and variance

---

## Technical Implementation

- Markov Regime-Switching models (via `statsmodels` or custom implementation)
- Regime visualization and dating
- Model diagnostics and comparison
- Autoregressive extensions

**Libraries:**
- `pandas`, `numpy`
- `statsmodels`
- `matplotlib` / `seaborn`

---

## Repository Contents

- `Stochastic_Modeling_Regime_Switching.ipynb` ← Main executable notebook
- `report.pdf` ← Professional analysis and model comparison
- `requirements.txt`
- `data/` ← Collected time series datasets
- `figures/` ← Regime plots and model diagnostics
- `README.md`

---

## How to Run

```bash
git clone https://github.com/yourusername/MScFE-622-Regime-Switching-Time-Series-GWP2.git
cd MScFE-622-Regime-Switching-Time-Series-GWP2
pip install -r requirements.txt
jupyter notebook MScFE_622_GWP2_Regime_Switching.ipynb
