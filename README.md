<img src="assets/research-banner.svg" alt="Fakhruddin Hakim Hussain — Quantitative research and data science" width="100%">

I am a data scientist with around one year of professional experience and an **MSc in Statistics with Data Science, with Merit, from the University of Edinburgh**. My projects use statistics, numerical modelling and machine learning to investigate forecasting, financial risk and trading questions.

Previously, I worked on delivery staffing, customer-order forecasting and rider incentives at **Swiggy**, a food-delivery business, and promotion-planning models at **PUMA**. My earlier degree is an Integrated MSc in Chemistry from IIT Kharagpur. I am based in Bengaluru, India.

[Email](mailto:fakhruddin.h.h@gmail.com) · [All projects](PROJECTS.md) · [How I evaluate research](RESEARCH_APPROACH.md)

## Start with a question

| Project | What I investigated | Main finding |
|---|---|---|
| [**BTC/ETH spot–futures carry**](https://github.com/Fakhruddin12/btc-funding-carry) | When does a futures premium pay for trading costs and holding capital? | 19.35% simulated net return versus 16.81% for entering every eligible contract, including cash interest. |
| [**GridPulse: electricity demand**](https://github.com/Fakhruddin12/gridpulse) | Can past demand predict tomorrow's hourly electricity needs? | Average test error fell 43.3% versus copying the same hour from the previous week. |
| [**ClearCredit: repayment-history risk**](https://github.com/Fakhruddin12/clearcredit) | How much does repayment history add beyond the latest account record? | In the historical comparison, LightGBM captured 51.1% of defaults versus 48.0% with latest-month inputs, at the same 20% review workload. |
| [**Used-tractor prices — MSc dissertation**](https://github.com/Fakhruddin12/auction-price-prediction) | How much can cleaned auction records tell us about sale prices? | Median percentage error fell from 40.2% to 32.0% against quadratic regression. |
| [**River pollution — MSc dissertation**](https://github.com/Fakhruddin12/bayesian-river-water-quality) | How do direct-discharge and runoff contributions change over time? | Hierarchical time-varying models helped zinc and orthophosphate predictions, but not every pollutant. |
| [**Option-price calibration**](https://github.com/Fakhruddin12/operator-regularized-dupire) | Does an adaptive penalty recover volatility more reliably from sparse quotes? | Some pricing gains, but unstable known-volatility recovery and weaker performance on some unseen expiries. |

Each repository begins with the problem and result, then links to model details, evaluation and code. Results are labelled as simulations, historical report findings or executed prediction studies as appropriate. The [full index](PROJECTS.md) also covers market-state volatility forecasting, ride-hailing simulation, statistical coursework and earlier machine-learning notebooks.

## How I work

I start with a useful baseline and make the prediction target explicit. Then I check whether the extra model complexity helps, examine where it fails and keep the result traceable to evidence. In the credit-risk study, matched-workload comparisons showed the value of repayment history, while targeted controls found no clear capture advantage from recurrence over a tree model.

**Programming:** Python · R · SQL · C++  
**Methods:** time series · Bayesian inference · machine learning · numerical optimisation · stochastic simulation  
**Tools:** NumPy · pandas · SciPy · scikit-learn · PyTorch · LightGBM · CatBoost · brms/Stan · DuckDB · Git · Databricks · Snowflake

I am interested in **quantitative research and data science roles** where careful analysis and collaboration turn models into useful decisions.
