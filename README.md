# Wenqi Ding

Computational finance undergraduate focused on transparent, reproducible empirical research in equity factor investing and credit-risk machine learning.

[TODO: add university, major, and expected graduation year]
[TODO: add a professional email or personal website if desired]

## Research Interests

- Empirical factor research
- Quantitative finance
- Credit-risk machine learning

## Technical Stack

- Python: pandas, NumPy, scikit-learn, statsmodels, LightGBM
- Research: factor IC/ICIR, quantile returns, portfolio backtesting, performance attribution
- Tools: Git, GitHub Actions, Streamlit, JupyterLab
- Data: deterministic simulated panels (current); Tushare and Yahoo Finance integration (planned)

## Featured Work

**Application and CV link:** use only
[quant-factor-research](https://github.com/WenqiDing-CompFin/quant-factor-research)
as the primary project URL. The other repositories are supporting demonstrations,
not competing headline projects.

| Project | Role in the portfolio | What to review |
|---|---|---|
| [Reproducible Multi-Factor Equity Research](https://github.com/WenqiDing-CompFin/quant-factor-research) | Flagship research project | Synthetic pipeline validation plus official Fama-French factor and momentum-decile evidence, dependence-aware inference, failure analysis, and reproducible artifacts |
| [Quant Factor Lab](https://github.com/WenqiDing-CompFin/quant-factor-lab) | [Interactive demo](https://quant-factor-lab-e5njhisnnujmsbatyy9dyz.streamlit.app/) | A clearly labeled synthetic Streamlit interface for exploring the flagship project's factor workflow |
| [Financial Time-Series Baseline](https://github.com/WenqiDing-CompFin/AAAI-Financial-TimeSeries) | Forecasting baseline / scaffold | Synthetic harness plus an official aggregate-market held-out Ridge baseline; not a complete TimeCAP reproduction |

[TODO: add credit-risk-loan-prediction to the table once the repository is public]

## Current Data Boundary

My factor research repository currently uses a **deterministic simulated panel** to validate the research pipeline: leakage controls, chronological splits, transaction costs, and reproducibility. These results are pipeline evidence, not market alpha. The next planned step is to integrate real market data while preserving the same research interface.

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

[TODO: add a short sentence about a specific course project or research goal]

Python is my primary research language. The repositories above include setup instructions, automated tests, and generated outputs so reviewers can reproduce the work rather than relying on screenshots or unsupported performance claims.
