<img src="assets/research-banner.svg" alt="Fakhruddin Hakim Hussain — Quantitative research and data science" width="100%">

I use statistics, mathematical modelling and machine learning to study noisy data and make better predictions. My work spans **volatility modelling, energy forecasting, credit risk and Bayesian inference**.

**University of Edinburgh** · MSc Statistics with Data Science, 2025–2026  
**IIT Kharagpur** · Integrated MSc Chemistry, 2024  
Previous experience includes data science at **Swiggy** and **PUMA**, and quantitative research at **AR Quants**.

[Email](mailto:Fakhruddin.h.h@gmail.com) · [All projects](PROJECTS.md) · [Research approach](RESEARCH_APPROACH.md)

## Start with the work closest to your role

| Quantitative research | Data science |
|:---|:---|
| [**Local-volatility calibration**](https://github.com/Fakhruddin12/operator-regularized-dupire) — PDE pricing, inverse problems and controlled regularizer comparisons | [**GridPulse**](https://github.com/Fakhruddin12/gridpulse) — day-ahead electricity-demand forecasting and chronological evaluation |
| [**HMM volatility forecasting**](https://github.com/Fakhruddin12/hmm-regime-volatility-forecasting) — hidden-state inference implemented from scratch | [**ClearCredit**](https://github.com/Fakhruddin12/clearcredit) — default-risk ranking, calibration and SQL feature engineering |
| [**Bayesian river modelling**](https://github.com/Fakhruddin12/bayesian-river-water-quality) — censored likelihoods and interpretable source models | [**Auction-price prediction**](https://github.com/Fakhruddin12/auction-price-prediction) — messy data, categorical modelling and error analysis |

## Selected findings

| Project | Question | Finding and evidence |
|:---|:---|:---|
| **GridPulse** | Can a simple model compete with a neural forecast? | Ridge achieved **1,164 MW holdout MAE**, **43.3% below** the weekly baseline; it also beat the TCN on validation. [Metrics](https://github.com/Fakhruddin12/gridpulse/blob/master/reports/metrics.json) |
| **ClearCredit** | How well can default risk be ranked and calibrated? | Calibrated LightGBM achieved **0.547 average precision** and **0.774 ROC-AUC** on a held-out historical sample. [Metrics](https://github.com/Fakhruddin12/clearcredit/blob/master/reports/uci/metrics.json) |
| **Auction prices** | How much do nonlinear models help with mixed currencies and sparse specifications? | CatBoost reduced test MedAPE from **40.2% to 32.0%**. [Study](https://github.com/Fakhruddin12/auction-price-prediction/blob/master/reports/RESULTS.md) |
| **HMM volatility** | Does separating regimes improve forward-volatility forecasts? | **11.69% lower RMSE** than a historical-volatility baseline; the extra benefit over a global random forest was small. [Daily and weekly checks](https://github.com/Fakhruddin12/hmm-regime-volatility-forecasting/blob/main/docs/RESULTS.md) |
| **Inverse Dupire** | Does an adaptive penalty improve local-volatility recovery? | A **50-fold comparison** found mixed pricing results and unstable known-truth recovery. [Full evidence](https://github.com/Fakhruddin12/operator-regularized-dupire/blob/main/docs/RESULTS.md) |
| **Bayesian river models** | How should below-detection measurements and changing pollution sources be modelled? | Adding flow improved held-out likelihood in **18 of 23 series** in the dissertation. [Results and reproduction status](https://github.com/Fakhruddin12/bayesian-river-water-quality/blob/master/README.md) |

## How I work

I start with a clear question, compare against a useful baseline, keep evaluation data separate from model selection, and inspect where the model fails. I document negative results alongside positive ones: a more complex model has to earn its place.

**Languages:** Python · R · SQL · C++  
**Methods:** time series · Bayesian inference · statistical learning · numerical optimisation · stochastic simulation  
**Tools:** NumPy · pandas · SciPy · scikit-learn · PyTorch · LightGBM · CatBoost · brms/Stan · DuckDB · Git  
**Industry tools:** Databricks · Snowflake

I am interested in **quantitative research and data science opportunities** where careful modelling, sound evaluation and clear communication matter.
