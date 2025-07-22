# MSDS451_Assignment2
Portfolio Optimization using Monte Carlo and Stochastic Programming

This project explores portfolio allocation across three assets using Monte Carlo simulation, constrained quadratic optimization, and stochastic programming. The goal is to determine optimal long/short strategies to maximize return given risk tolerance.

## Contents

- `MSDS451_Assignment2.ipynb`: Full notebook with code, analysis, and plots
- `MSDS451_Assignment2.html`: HTML export of the notebook
- `MSDS451_Assignment2_Report.pdf`: Final research report (LaTeX-formatted)

## Summary of Strategies

| Strategy              | Expected Return | Risk (Std. Dev.) |
|-----------------------|-----------------|------------------|
| Equal Weight          | ~9.75%          | ~0.0212          |
| Optimized (Quadratic) | ~11.19%         | ~0.0409          |
| Stochastic            | ~11.19%         | ~0.0409          |

## How to Run

1. Open `MSDS451_Assignment2.ipynb` in Google Colab (https://colab.research.google.com/) or a local Jupyter environment
2. Run all cells sequentially from top to bottom
3. Outputs (tables and plots) will be generated inline

No external datasets are required—the notebook simulates asset returns

## Research Report

The report (PDF) includes:
- Problem description
- Data generation and simulation
- Portfolio optimization using quadratic programming
- Stochastic programming formulation and solution
- Plots and analysis
- Conclusions and future work

## AI Usage Disclosure

ChatGPT was used to:
- Debug Python code for portfolio optimization
- Check report for spelling, grammar, miscellaneous errors

## Submission URL

GitHub Repository (cloneable): https://github.com/bcaldwell21/MSDS451_Assignment2.git
