# Household Food Expenditure Share

A statistical analysis of the factors influencing household food
expenditure share, using microdata from the 2024 U.S. Consumer
Expenditure Survey. The project explores whether income, age, and
other household characteristics are meaningfully associated with the
share of spending allocated to food — a question rooted in Engel's Law.

Built with **R**, **Quarto**, and the **tidyverse**.

## What's inside

- `report.qmd` — the full analysis (data processing, EDA, hypothesis testing)
- `report.pdf` — rendered report

## Summary

Starting from ~12,000 household records, the analysis cleans and
aggregates the data, explores relationships through visualisation, and
tests them with Welch two-sample t-tests. Both income and age of the
reference person show a statistically significant association with food
share, consistent with Engel's Law — though the practical differences
are modest.

Full methodology and results are in the report.

## Data

2024 U.S. Consumer Expenditure Survey (FMLI files), U.S. Bureau of
Labor Statistics: https://www.bls.gov/cex/pumd_data.htm
