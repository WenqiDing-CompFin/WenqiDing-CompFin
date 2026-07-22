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
| [Reproducible Multi-Factor Equity Research](https://github.com/WenqiDing-CompFin/quant-factor-research) | Flagship research project | Point-in-time signal design, Rank IC, quantile tests, cost-aware backtest, regression tests, failure register, and reproducible artifacts |
| [Quant Factor Lab](https://github.com/WenqiDing-CompFin/quant-factor-lab) | Interactive demo | A deployed Streamlit interface for exploring the flagship project's factor workflow |
| [Financial Time-Series Baseline](https://github.com/WenqiDing-CompFin/AAAI-Financial-TimeSeries) | Forecasting baseline / scaffold | Chronological train/validation/test design, validation-only model selection, held-out metrics, and reproducible tests |

## Research Principles

- Keep targets and future information outside feature construction.
- Compare models and strategies with transparent baselines.
- Report weak and negative findings alongside favorable results.
- Make assumptions, data provenance, costs, and claim boundaries inspectable.
- Treat synthetic experiments as pipeline validation, not market evidence.

## Current Direction

I am extending the factor research pipeline toward legally usable point-in-time
market data, frozen out-of-sample evaluation, sector and size neutralization,
and more realistic implementation-cost analysis. In parallel, I am developing
the financial time-series repository from a rigorous baseline into a documented
event-context modeling study.

Python is my primary research language. The repositories above include setup
instructions, automated tests, and generated outputs so reviewers can reproduce
the work rather than relying on screenshots or unsupported performance claims.
