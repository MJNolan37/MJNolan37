# Matthew Nolan

I build reproducible research tools to investigate market behavior, test hypotheses, and make uncertainty visible. My standard is simple: define the question clearly, challenge the result aggressively, and publish the limitations alongside the findings. I do this because it keeps me learning—new methods, new tools, and new ways a result can quietly be wrong.

[Explore the portfolio](https://github.com/MJNolan37/Portfolio) · [Research workflow](https://github.com/MJNolan37/ai-research-playbook)

## Start here

1. [V&D Cloud](https://github.com/MJNolan37/vd-cloud) — the most complete evidence path: question, tests, negative result, and Atlas.
2. [Project Parallax](https://github.com/MJNolan37/Project-Parallax) — research judgment and staged execution: coverage gate, preregistration, and an audit finding turned into a regression test.
3. [Options Positioning Research](https://github.com/MJNolan37/options-positioning-research) — synthetic-chain engineering with explicitly scoped validation and gap-aware descriptive charts.

## Featured Research

### V&D Cloud — Volatility & Dispersion Regime Research
**Question:** Can the Ichimoku cloud's regime logic work on volatility and dispersion instead of price?
**Method:** HAC/Newey-West inference, permutation diagnostics, simple-baseline comparisons, and retrospective chronological stability analysis, across QQQ and a developed-market ETF surface.
**Finding:** The revised analysis did not establish predictive validity or a consistent advantage over simpler baselines. The [canonical evidence table](https://github.com/MJNolan37/vd-cloud#verified-revised-results) separates exploratory threshold crossings from validated findings. No selection or multiplicity correction was applied; the later period was retrospective, not an untouched holdout.
**Includes:** Atlas Observatory, an interactive single-ticker dashboard for monitoring volatility and dispersion states without making forecasting claims.

[Repository](https://github.com/MJNolan37/vd-cloud) · [Live dashboard](https://mjnolan37.github.io/vd-cloud/)

### Project Parallax — Equity Dispersion & Attribution
**Question:** Has the balance between market-, industry- and firm-specific equity return variation changed?
**Work:** A public-data variance decomposition for 2010–2024, staged validation and a frozen Phase 2 specification.
**Status:** Phase 1 is complete. At the [October 25, 2026 snapshot](https://github.com/MJNolan37/Project-Parallax/blob/38411cc050696efde85d7702c9a11b9ad985c693/docs/A1_STATUS.md), the H1 critical value remained unresolved and empirical H1/H2 analysis had not been run. The sample uses current S&P 500 members projected backward, with survivorship bias of unknown direction and magnitude.

[Repository](https://github.com/MJNolan37/Project-Parallax) · [Validation-gate case study](https://github.com/MJNolan37/ai-research-playbook/blob/main/case-studies/parallax-validation-gate.md)

### Options Positioning Research
**Question:** Can longitudinal option-chain data be transformed into stable, interpretable positioning features suitable for future quantitative research?
**Method:** A documented synthetic option-chain generator anchored to a real underlying price, wide-to-long normalization, eight engineered positioning/liquidity features, and a 12-check validation suite covering both data integrity and the generator's own shape rules.
**Status:** The saved 2026-07-20 synthetic single-snapshot report (2,090 contracts) records 10 pass, 2 informational, 0 fail. The 65-date series has descriptive analysis, but no published full-series 12-check report. See the [named saved-output summary](https://github.com/MJNolan37/options-positioning-research/blob/main/results/published_check_summary.json). No predictive or trading claim.

[Repository](https://github.com/MJNolan37/options-positioning-research)

## Research Workflow

[AI Research Playbook](https://github.com/MJNolan37/ai-research-playbook) documents how I scope AI-assisted work, check evidence, retain decision authority and record what I learn. It includes a Parallax case study and reusable charter, handoff and decision templates.

## Methods & Tools

Methods: HAC/Newey-West inference · random-label permutation testing · retrospective chronological stability analysis · baseline challenges · synthetic-data generation · schema and integrity testing

Tools: Python · pandas · NumPy · statsmodels · scikit-learn · Plotly · Matplotlib · Jupyter · Git

The research projects use public or synthetic data. AI tools assist with coding and review; I own the research questions, methodological decisions and final interpretations.

## License

Copyright © 2026 Matthew Nolan (MJNolan37). Except where otherwise noted, the original text and diagrams in this repository are licensed under [CC BY 4.0](LICENSE). Linked repositories, external material and third-party assets retain their own licenses and terms.
