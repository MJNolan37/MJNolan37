# Matthew Nolan

I build reproducible research tools to investigate market behavior, test hypotheses, and make uncertainty visible. My standard is simple: define the question clearly, challenge the result aggressively, and publish the limitations alongside the findings. I do this because it keeps me learning—new methods, new tools, and new ways a result can quietly be wrong.

## Featured Research

### V&D Cloud — Volatility & Dispersion Regime Research
**Question:** Can volatility and cross-sectional dispersion support a stable and recurring classification of market regimes?
**Method:** HAC/Newey-West inference, random-label permutation testing, baseline challenges, and a chronological out-of-sample holdout, across QQQ and a developed-market ETF surface.
**Finding:** Of 13 rigorously tested candidate regimes, 1 cleared both robustness bars — a result consistent with chance under multiple-comparison correction. Reported as a negative result, not reframed as a win.
**Includes:** Atlas Observatory, an interactive single-ticker dashboard for monitoring volatility and dispersion states without making forecasting claims.

[Repository](https://github.com/MJNolan37/vd-cloud) · [Live dashboard](https://mjnolan37.github.io/vd-cloud/atlas/)

### Options Positioning Research
**Question:** Can longitudinal option-chain data be transformed into stable, interpretable positioning features suitable for future quantitative research?
**Method:** A documented synthetic option-chain generator anchored to a real underlying price, wide-to-long normalization, eight engineered positioning/liquidity features, and a 12-check validation suite covering both data integrity and the generator's own shape rules.
**Status:** Engineering and validation complete; deliberately stops before prediction or trading claims.

[Repository](https://github.com/MJNolan37/options-positioning-research)

## Methods & Tools

Methods: HAC/Newey-West inference · random-label permutation testing · chronological out-of-sample validation · baseline challenges · synthetic-data generation · schema and integrity testing

Tools: Python · pandas · NumPy · statsmodels · scikit-learn · Plotly · Matplotlib · Jupyter · Git

All published work is independently developed using public or synthetic data.

## Portfolio Index

Additional context and navigation across the published projects are available in the [Portfolio index](https://github.com/MJNolan37/Portfolio).
