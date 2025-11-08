{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "fddfa75f-2395-4846-9f70-f916e295db6a",
   "metadata": {},
   "source": [
    "# Extreme Risk & Value-at-Risk Estimation\n",
    "\n",
    "This repository presents a curated collection of statistical techniques widely used in finance to model extreme events and tail risk, implemented and visualized in Python. Each notebook demonstrates a core method applied to synthetic or simulated asset returns, emphasizing accuracy, reproducibility, and practical insight into risk estimation. The objective is to bridge theoretical finance with hands-on implementation for modeling downside risk and evaluating Value-at-Risk (VaR) under different distributional assumptions.\n",
    "\n",
    "## Overview\n",
    "This collection showcases key approaches for tail-risk and extreme value modeling:\n",
    "\n",
    "| # | Notebook Title | Focus | Key Concepts |\n",
    "|---|----------------|-------|--------------|\n",
    "| 1 | Synthetic Return Modeling & Tail-Risk Foundations | Synthetic returns & distributional insight | Simulation of light, medium, and heavy-tailed returns; descriptive statistics; QQ-plots; empirical quantiles |\n",
    "| 2 | Parametric VaR Estimation via Cornish-Fisher & Student-T | Parametric tail-risk estimation | Cornish-Fisher expansion; Student-t VaR; comparison to empirical quantiles |\n",
    "| 3 | Student-t VaR Estimation via Tail-Risk Analysis for Heavy-Tailed Assets | Heavy-tailed tail-risk modeling | Fitting Student-t via MLE; degrees of freedom estimation; parametric Student-t VaR vs Normal & empirical; histogram with PDF overlay |\n",
    "| 4 | EVT-Based Value-at-Risk via Gumbel & Fréchet Tail Modeling | Extreme Value Theory & block maxima | EVT block maxima method; Gumbel & Frechet distributions; EVT-based VaR computation; visualization vs empirical losses |\n",
    "\n",
    "## Technical Highlights\n",
    "Each notebook is written for clarity, reproducibility, and quantitative rigor, combining theoretical context with clean Python implementation.\n",
    "\n",
    "Key methods demonstrated:\n",
    "\n",
    "- Synthetic Data Simulation: Generates controlled return distributions for different tail behaviors.\n",
    "- Empirical & Parametric VaR: Quantile-based risk estimation using Normal, Student-t, Cornish-Fisher, Gumbel, and Frechet models.\n",
    "- Extreme Value Theory (EVT): Block maxima approach for modeling rare, extreme events; fitting Gumbel and Frechet distributions.\n",
    "- Distribution Fitting & Diagnostics: Maximum likelihood estimation, skewness, excess kurtosis, and QQ-plot analysis.\n",
    "- Visualization: Histograms with overlaid PDFs to illustrate tail behavior and distributional fit.\n",
    "\n",
    "## Practical Applications\n",
    "These techniques are foundational in:\n",
    "\n",
    "- Risk Management: Modeling tail exposures and extreme losses for portfolio analysis.\n",
    "- Quantitative Research: Understanding and comparing statistical models for extreme events.\n",
    "- Stress Testing & Scenario Analysis: Evaluating potential market shocks using parametric and EVT-based VaR.\n",
    "- Model Validation: Assessing accuracy of parametric and non-parametric tail-risk measures.\n",
    "\n",
    "## Technical Environment\n",
    "All notebooks are written in Python 3 and require the following packages:\n",
    "\n",
    "```text\n",
    "numpy\n",
    "scipy\n",
    "pandas\n",
    "matplotlib\n",
    "seaborn\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "542d64c4-bd84-4dd3-8dc1-895fdd94bd30",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.14.0"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
