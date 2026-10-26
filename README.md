# Matthew Nolan

## Start here

1. [V&D Cloud](https://github.com/MJNolan37/vd-cloud) — the most complete evidence path: question, tests, negative result, and Atlas.
2. [Project Parallax](https://github.com/MJNolan37/Project-Parallax) — research judgment and staged execution: coverage gate, preregistration, and an audit finding turned into a regression test.

I build reproducible research tools to investigate market behavior, test hypotheses, and make uncertainty visible. My standard is simple: define the question clearly, challenge the result aggressively, and publish the limitations alongside the findings. I do this because it keeps me learning—new methods, new tools, and new ways a result can quietly be wrong.

## Featured Research

### V&D Cloud — Volatility & Dispersion Regime Research
**Question:** Can the Ichimoku cloud's regime logic work on volatility and dispersion instead of price?
**Method:** HAC/Newey-West inference, permutation diagnostics, simple-baseline comparisons, and retrospective chronological stability analysis, across QQQ and a developed-market ETF surface.
**Finding:** The revised analysis did not establish predictive validity or a consistent advantage over simpler baselines. The [canonical evidence table](https://github.com/MJNolan37/vd-cloud#verified-revised-results) separates exploratory threshold crossings from validated findings. No selection or multiplicity correction was applied; the later period was retrospective, not an untouched holdout.
**Includes:** Atlas Observatory, an interactive single-ticker dashboard for monitoring volatility and dispersion states without making forecasting claims.

[Repository](https://github.com/MJNolan37/vd-cloud) · [Live dashboard](https://mjnolan37.github.io/vd-cloud/atlas/)

### Options Positioning Research
**Question:** Can longitudinal option-chain data be transformed into stable, interpretable positioning features suitable for future quantitative research?
**Method:** A documented synthetic option-chain generator anchored to a real underlying price, wide-to-long normalization, eight engineered positioning/liquidity features, and a 12-check validation suite covering both data integrity and the generator's own shape rules.
**Status:** Engineering and validation complete; deliberately stops before prediction or trading claims.

[Repository](https://github.com/MJNolan37/options-positioning-research)

## Methods & Tools

Methods: HAC/Newey-West inference · random-label permutation testing · retrospective chronological stability analysis · baseline challenges · synthetic-data generation · schema and integrity testing

Tools: Python · pandas · NumPy · statsmodels · scikit-learn · Plotly · Matplotlib · Jupyter · Git

All published work is independently developed using public or synthetic data.

## Portfolio Index

Additional context and navigation across the published projects are available in the [Portfolio index](https://github.com/MJNolan37/Portfolio).
