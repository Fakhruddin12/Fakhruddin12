# Research approach

My projects are built around questions that can fail an empirical test.

1. **Define the estimand or prediction target.** A fitted option surface, future realised volatility and realised trading returns answer different questions.
2. **Use an informative baseline.** A global random forest tests whether regime separation helps; seasonal naive forecasts test whether demand modelling adds value; H1/H2 penalties test whether an adaptive regularizer earns its complexity.
3. **Separate selection from evaluation.** Use chronological splits for forecasting and training-only preprocessing. Label random-split studies and exploratory comparisons clearly.
4. **Inspect uncertainty and failure.** Check numerical discretisation, sensitivity to random draws, subgroup errors and the incremental value of each component.
5. **Keep claims traceable.** Each number should lead to a saved table, report or a reproducible experiment. Historical results are labelled when their complete inputs are unavailable.

The [Dupire study](https://github.com/Fakhruddin12/operator-regularized-dupire) is an example: attractive early recovery results did not become a blanket superiority claim when the broader audit produced mixed outcomes.
