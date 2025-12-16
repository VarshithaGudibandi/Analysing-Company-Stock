# Netflix Stock Analysis: Beta Regression + Efficient Frontier (with Microsoft)

## Overview
Analyzed Netflix stock risk/return vs. the market and constructed a two-asset efficient frontier with Microsoft.
Data: 156-week period ending Oct 7, 2024.

## Business Questions
- How sensitive is Netflix to overall market movements (beta)?
- What risk/return tradeoff can an investor achieve by combining Netflix with Microsoft?

## Key Results
- Beta (Netflix vs. Wilshire 5000): 1.62
- Beta (Microsoft vs. Wilshire 5000): 1.09
- Built an efficient frontier showing optimal risk-return allocations of Netflix + Microsoft.

## Method (Excel-first)
- Collected weekly adjusted close prices (Yahoo Finance) and computed weekly returns
- Ran regression of stock returns vs. Wilshire 5000 returns to estimate beta
- Estimated expected returns using: Risk-free rate (4.875%) + Beta × Equity risk premium (7.8%)
- Computed portfolio return and volatility across weight allocations and plotted the efficient frontier

## Artifacts
- Report: `docs/Analysing_Company_Stock.pdf`
- Excel model: `docs/Analysing_Company_Stock.xlsx`
- Figures: `assets/regression_beta.png`, `assets/efficient_frontier.png`

## Notes
Completed as part of a Corporate Finance course assignment.
