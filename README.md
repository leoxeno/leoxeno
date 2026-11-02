# Stavros Stavroglou

Assistant Professor in FinTech, University of Edinburgh Business School, and applied mathematician. I build forecasting and risk tools that other people use to make decisions with money, and I ship the research methods as software others can run.

**Industry work.** Consulting for a UK asset manager on portfolio risk (multifactor equity risk buckets, 2026) and for a UK bank on SME credit scoring (2025) and demand forecasting across banking products (2024). Earlier: Data Scientist at Financial Network Analytics, London, where I analysed lead-lag correlations across portfolios of bank bonds and bond ETFs, looking through each ETF to the bonds it holds, and that analysis fed an analytics product a German investment bank piloted for portfolio risk assessment and construction; AI Consultant at Mind.AI, Seoul, where I built the order logic of an inventory decision system for a supermarket chain in Thailand, used by its central replenishment team (client-reported 40% fewer out-of-stock items in the pilot); co-founder and CEO of Prediction Tech, Athens, a three-person consultancy that built demand forecasts for nine luxury hotel brands.

**[Model arena](https://github.com/leoxeno/forecast-arena).** The evaluation harness behind the AION benchmark: one expanding-window protocol with fifteen origins per series; 170 model wrappers over 34 libraries, from ridge and XGBoost to N-BEATS, Transformers and fifteen zero-shot time-series foundation models, behind one `Forecaster` base class; a 20-series task atlas spanning chaotic systems, astrophysics, hydrology, climate, macroeconomics, finance and ecology; leaderboards that unrank any model with a failed origin; Diebold-Mariano, block-bootstrap and Friedman-Nemenyi tests. The evaluation harness is public under Apache-2.0. AION's method code remains in a separate private repository; the manuscript is in preparation.

**Pattern Causality** recovers directed causal structure between time series from their reconstructed dynamics and separates positive, negative and dark causality. Two papers in *PNAS*: [Hidden interactions in financial markets](https://doi.org/10.1073/pnas.1819449116) (2019) and [Unveiling causal interactions in complex systems](https://doi.org/10.1073/pnas.1918269117) (2020).

- R package, on CRAN: [pattern-causality/pattern_causality](https://github.com/pattern-causality/pattern_causality)
- Python package, on PyPI: [pattern-causality/pattern_causality_py](https://github.com/pattern-causality/pattern_causality_py)

**AION**, an adaptive geometric machine learning forecasting framework for macroeconomic and market series, is in preparation.

- University profile: https://www.business-school.ed.ac.uk/staff/stavros-stavroglou
- Google Scholar: https://scholar.google.co.uk/citations?user=jpSj6xgAAAAJ&hl=en
- ORCID: https://orcid.org/0000-0003-3931-0391
