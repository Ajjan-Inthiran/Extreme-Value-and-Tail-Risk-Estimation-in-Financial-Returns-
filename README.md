# Extreme Risk & Value-at-Risk Estimation

This repository presents a curated collection of statistical techniques widely used in finance to model extreme events and tail risk, implemented and visualized in Python. Each notebook demonstrates a core method applied to synthetic or simulated asset returns, emphasizing accuracy, reproducibility, and practical insight into risk estimation. The objective is to bridge theoretical finance with hands-on implementation for modeling downside risk and evaluating Value-at-Risk (VaR) under different distributional assumptions.

## Overview
This collection showcases key approaches for tail-risk and extreme value modeling:

| # | Notebook Title | Focus | Key Concepts |
|---|----------------|-------|--------------|
| 1 | Synthetic Return Modeling & Tail-Risk Foundations | Synthetic returns & distributional insight | Simulation of light, medium, and heavy-tailed returns; descriptive statistics; QQ-plots; empirical quantiles |
| 2 | Parametric VaR Estimation via Cornish-Fisher & Student-T | Parametric tail-risk estimation | Cornish-Fisher expansion; Student-t VaR; comparison to empirical quantiles |
| 3 | Student-t VaR Estimation via Tail-Risk Analysis for Heavy-Tailed Assets | Heavy-tailed tail-risk modeling | Fitting Student-t via MLE; degrees of freedom estimation; parametric Student-t VaR vs Normal & empirical; histogram with PDF overlay |
| 4 | EVT-Based Value-at-Risk via Gumbel & Fréchet Tail Modeling | Extreme Value Theory & block maxima | EVT block maxima method; Gumbel & Frechet distributions; EVT-based VaR computation; visualization vs empirical losses |

## Technical Highlights
Each notebook is written for clarity, reproducibility, and quantitative rigor, combining theoretical context with clean Python implementation.

Key methods demonstrated:

- Synthetic Data Simulation: Generates controlled return distributions for different tail behaviors.
- Empirical & Parametric VaR: Quantile-based risk estimation using Normal, Student-t, Cornish-Fisher, Gumbel, and Frechet models.
- Extreme Value Theory (EVT): Block maxima approach for modeling rare, extreme events; fitting Gumbel and Frechet distributions.
- Distribution Fitting & Diagnostics: Maximum likelihood estimation, skewness, excess kurtosis, and QQ-plot analysis.
- Visualization: Histograms with overlaid PDFs to illustrate tail behavior and distributional fit.

## Practical Applications
These techniques are foundational in:

- Risk Management: Modeling tail exposures and extreme losses for portfolio analysis.
- Quantitative Research: Understanding and comparing statistical models for extreme events.
- Stress Testing & Scenario Analysis: Evaluating potential market shocks using parametric and EVT-based VaR.
- Model Validation: Assessing accuracy of parametric and non-parametric tail-risk measures.

## Technical Environment
All notebooks are written in Python 3 and require the following packages:

```text
numpy
scipy
pandas
matplotlib
seaborn
