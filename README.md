# Linear_Factor_Decomposition

Quantitative analysis of hedge fund replication ETFs and factor models benchmarked against the HFRI Fund Weighted Composite Index, covering performance, tail risk, regression diagnostics, and rolling out-of-sample replication.

# Overview

This notebook evaluates how well liquid, low-cost replication vehicles — ProShares ETFs (HDG, QAI) and the Merrill Lynch Factor Model series — track the return and risk characteristics of the HFRI Fund Weighted Composite Index. Analysis spans summary statistics, tail risk, factor regressions, correlation structure, and both in-sample and out-of-sample replication performance.

# Key Findings

The ML Factor Model captures HFRI's statistical properties more faithfully than HDG, with lower market beta and comparable tail-risk profile
QAI outperforms HDG on a risk-adjusted basis across Treynor ratio, information ratio, and downside metrics
In-sample replication achieves R² ≈ 0.84 with annualized tracking error ~2.3%
Out-of-sample replication holds up well (OOS R² ≈ 0.81, correlation ~0.90) but underperforms HFRI on average return, reflecting alpha leakage and nonlinear strategy exposure the factor model cannot capture
