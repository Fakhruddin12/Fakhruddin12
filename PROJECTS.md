# Project Index

Choose a question first; the linked README introduces the work before its technical details. Evidence and reproduction limits are kept visible so reported results are not mistaken for newly rerun experiments or live business outcomes.

| Project | Question and my work | Evidence to inspect |
|---|---|---|
| [BTC/ETH spot–futures carry](https://github.com/Fakhruddin12/btc-funding-carry) | Test whether futures premiums pay for execution, collateral and cash opportunity cost. | 44-contract backtest, cost/risk accounting, input hashes and 31 tests. |
| [Option-price / Dupire calibration](https://github.com/Fakhruddin12/operator-regularized-dupire) | Fit a volatility surface from sparse prices and test location-dependent penalties. | 50-fold audit, pricing and known-truth recovery checks, including failures. |
| [Volatility across market states](https://github.com/Fakhruddin12/hmm-regime-volatility-forecasting) | Build hidden-state inference from scratch and compare next-five-day volatility forecasts. | Causal state filtering, chronological labels and non-overlapping test controls. |
| [GridPulse: tomorrow's electricity demand](https://github.com/Fakhruddin12/gridpulse) | Compare regression and neural forecasts of 24 hourly demand values. | Three validation windows, later test, peak-hour errors and interval coverage. |
| [ClearCredit: default-risk research](https://github.com/Fakhruddin12/clearcredit) | Test the value of repayment history beyond latest-month inputs and compare ordered, flattened and permuted neural representations. | [Matched-capacity findings](https://github.com/Fakhruddin12/clearcredit/blob/master/research/v3/RESULTS_SUMMARY.md), five-seed sensitivity and paired uncertainty; the cohort remains retrospective. |
| [River pollution — MSc dissertation](https://github.com/Fakhruddin12/bayesian-river-water-quality) | Estimate changing discharge/runoff contributions with nonlinear hierarchical Bayesian models. | Dissertation Table 5 and full pollutant comparison; archived code differs from the final model and needs restored inputs. |
| [Used-tractor prices — MSc dissertation](https://github.com/Fakhruddin12/auction-price-prediction) | Construct a clean auction-sale sample and test nonlinear price models. | Executed notebooks, 3,429 test sales and rare-series error analysis; source listings required for retraining. |
| [Ride-hailing simulation](https://github.com/Fakhruddin12/ride-hailing-simulation) | Co-build an event-driven passenger/driver system and measure service outcomes. | Executable example, unit conventions and team authorship; not a calibrated city forecast. |
| [Statistical modelling coursework](https://github.com/Fakhruddin12/statistical-modelling-studies) | Team studies of delayed infection signals, contact networks and multilevel associations. | R source, contribution records and study-specific input limits. |
| [Earlier machine-learning notebooks](https://github.com/Fakhruddin12/Machine-Learning-Projects) | Learning projects in classification, regression, language modelling and pairs discovery. | Seven folder guides; historical results are not promoted as current validated benchmarks. |

## Suggested routes

**Quantitative research:** carry trading → option-price calibration → volatility forecasting → Bayesian river models.  
**Data science:** credit risk → electricity demand → auction prices → Bayesian river models.  
**Statistics:** Bayesian river models → statistical coursework → simulation.

The earlier volatility notebook is superseded by the dedicated forward-volatility study. The Home Credit SQL extension is separate from the measured UCI credit-card experiments and has not been fully benchmarked.
