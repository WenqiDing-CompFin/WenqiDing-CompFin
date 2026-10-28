# Wenqi Ding

Computational finance undergraduate focused on transparent, reproducible empirical research in equity factor investing and credit-risk machine learning.

professional email: dingwenqi6@gmail.com

## Research Interests

- Empirical factor research
- Quantitative finance
- Credit-risk machine learning

## Technical Stack

- Python: pandas, NumPy, scikit-learn, statsmodels, LightGBM
- Research: factor IC/ICIR, quantile returns, portfolio backtesting, performance attribution
- Tools: Git, GitHub Actions, Streamlit, JupyterLab
- Data: deterministic simulated panels (default) and an experimental Tushare A-share adapter

## Featured Work

My main public research repository is
[quant-factor-research](https://github.com/WenqiDing-CompFin/quant-factor-research).
The other projects demonstrate complementary interfaces and forecasting methods.
The projects most relevant to an application depend on the research question and
the receiving program.

| Project | Role in the portfolio | What to review |
|---|---|---|
| [Reproducible Multi-Factor Equity Research](https://github.com/WenqiDing-CompFin/quant-factor-research) | Flagship research project | Synthetic pipeline validation plus official Fama-French factor and momentum-decile evidence, dependence-aware inference, failure analysis, and reproducible artifacts |
| [Quant Factor Lab](https://github.com/WenqiDing-CompFin/quant-factor-lab) | [Interactive demo](https://quant-factor-lab-e5njhisnnujmsbatyy9dyz.streamlit.app/) | A clearly labeled synthetic Streamlit interface for exploring the flagship project's factor workflow |
| [Financial Time-Series Baseline](https://github.com/WenqiDing-CompFin/AAAI-Financial-TimeSeries) | Forecasting baseline / scaffold | Synthetic harness plus a retrospective official aggregate-market Ridge comparison; historical availability is not verified and this is not a complete TimeCAP reproduction |


## Current Data Boundary

My factor research repository uses a **deterministic simulated stock panel** to
exercise timing checks, transaction costs, and reproducibility. The stock-level
simulation does not implement a train/validation/test split, and its results are
pipeline evidence, not market alpha. A separate module analyzes official aggregate
factor returns; it does not validate the stock-selection strategy. The A-share
adapter is experimental and requires further point-in-time and execution checks.

## Research Principles

- Keep targets and future information outside feature construction.
- Compare models and strategies with transparent baselines.
- Report weak and negative findings alongside favorable results.
- Make assumptions, data provenance, costs, and claim boundaries inspectable.
- Treat synthetic experiments as pipeline validation, not market evidence.

## Future Research Directions

- Point-in-time real data integration for China A-shares and US equities
- Walk-forward out-of-sample evaluation and factor-decay monitoring
- Multiple-testing controls and deflated performance measures
- Credit-risk model interpretation and validation


Python is my primary research language. The repositories above include setup instructions, automated tests, and generated outputs so reviewers can reproduce the work rather than relying on screenshots or unsupported performance claims.
