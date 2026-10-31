# How I Evaluate Research

A model is useful only if the question, comparison and evidence support the intended conclusion. These are the checks I use across this portfolio.

1. **Define what is being estimated.** An option price, an unobserved pollution source, next-month default and trading P&L are different targets. Being good at one does not automatically establish the other.
2. **Choose a baseline that challenges the idea.** Copying last week's electricity demand tests basic forecasting value. One random forest across all market states tests whether regime separation is worth adding. A simpler volatility surface challenges a more elaborate calibration penalty.
3. **Keep selection separate from reporting.** Use training-only transformations and time-aware evaluation where the data allow it. A previously inspected reporting sample cannot become an untouched test set merely by naming it one.
4. **Translate scores into their practical meaning.** Default capture at a fixed workload is easier to interpret than an isolated probability score. Simulated trading returns need costs, cash interest and a benchmark explained alongside them.
5. **Investigate failures as part of the result.** Check errors in hard groups, numerical instability, missing-input sensitivity and whether the main conclusion survives an alternative evaluation.
6. **Keep every claim traceable.** Link to the table, report or code. Distinguish executed results from dissertation findings whose original inputs are incomplete, and retain team contributions.

## Examples

- [ClearCredit](https://github.com/Fakhruddin12/clearcredit): full-history LightGBM captured 51.1% of defaults versus 48.0% using latest-month inputs at the same review workload. The GRU had no clear capture advantage over the tree model. A separate subgroup analysis also distinguished low recall under a global review threshold from the ability to rank accounts within that subgroup. These results remain retrospective.
- [Volatility forecasting](https://github.com/Fakhruddin12/hmm-regime-volatility-forecasting): the model beat a simple historical forecast, but one random forest was nearly as good as the regime-specific models.
- [Option-price calibration](https://github.com/Fakhruddin12/operator-regularized-dupire): lower pricing error in some comparisons did not imply reliable recovery of the true volatility surface.
- [River modelling](https://github.com/Fakhruddin12/bayesian-river-water-quality): changing source terms improved some pollutants and made ammonia predictions worse, so a single preferred model for every pollutant was not justified.

[Project index](PROJECTS.md) · [Profile](README.md)
