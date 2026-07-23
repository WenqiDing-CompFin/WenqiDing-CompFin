# Wenqi Ding

I study computational finance, quantitative equity research, and financial time
series. My public projects emphasize reproducibility, explicit timing rules,
honest failure analysis, and a clear boundary between software validation and
evidence from real markets.

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

## Research Principles

- Keep targets and future information outside feature construction.
- Compare models and strategies with transparent baselines.
- Report weak and negative findings alongside favorable results.
- Make assumptions, data provenance, costs, and claim boundaries inspectable.
- Treat synthetic experiments as pipeline validation, not market evidence.

## Current Direction

The current public evidence uses official aggregate factor and
characteristic-sorted portfolios. The next research stage is security-level
point-in-time data with frozen model selection, sector and size neutralization,
and more realistic implementation-cost analysis. In parallel, the forecasting
scaffold provides the evaluation harness required before any event-context model
or TimeCAP-inspired extension can make a credible comparison.

Python is my primary research language. The repositories above include setup
instructions, automated tests, and generated outputs so reviewers can reproduce
the work rather than relying on screenshots or unsupported performance claims.
