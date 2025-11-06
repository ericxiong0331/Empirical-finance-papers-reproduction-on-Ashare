# Empirical-finance-papers-reproduction-on-Ashare
Reproduction on empirical finance papers using A-share data

## Project Overview

This project systematically reproduces three influential empirical finance studies to assess their robustness and generalizability within China's A-share market. Meanwhile, the accompanying presentation slides interpret the theoretical background, research design and empirical findings of each study.

## Project Scope

- Asset growth factor decomposition: Testing alternative investment metrics and subcomponents (inventory, INVT and accounts receivable, AREC) against traditional models, with two-pass regression and quantile portfolios to capture factor heterogeneity.

- Equity premium forecasting: Implementing combined forecasting methods (mean, median, DMSPE) to compare multi-factor combination models against univariate models and historical average baselines.

- Green bond event analysis: Applying event-study methodology (CAR estimation) to evaluate market reactions to corporate green bond issuances in China.

## Paper Sources:
- Factor model: Michael Cooper, Huseyin Gulen, Mihai Ion, The use of asset growth in empirical asset pricing models,
Journal of Financial Economics, Volume 151, 2024, 103746, ISSN 0304-405X, https://doi.org/10.1016/j.jfineco.2023.103746.

- Time series prediction: David E. Rapach, Jack K. Strauss, Guofu Zhou, Out-of-Sample Equity Premium Prediction: Combination Forecasts and Links to the Real Economy, The Review of Financial Studies, Volume 23, Issue 2, February 2010, Pages 821–862, https://doi.org/10.1093/rfs/hhp063

- Event study: Caroline Flammer, Corporate green bonds, Journal of Financial Economics, Volume 142, Issue 2,
2021, Pages 499-516, ISSN 0304-405X, https://doi.org/10.1016/j.jfineco.2021.01.010.

## Key Contributions

- Successfully replicated and validated main findings of the original papers in the A-share context, showing model consistency across market environments.
- Advances methodological transparency and accessibility, with promotion of standardized empirical finance workflows by providing open-source Jupyter notebooks and data.
- Effectively bridging academic rigor with practical insight for researchers and practitioners. Provided robust cross-market evidence for empirical asset pricing research. 

## Technologies & Techniques

- **Database:** CSMAR, Wind
- **Operations:** Data cleaning, feature engineering, descriptive statistic, visualization, baseline model, regression models
- **Programming:** Python
- **Libraries:** pandas, statsmodels, linearmodels, matplotlib
