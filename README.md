# 25 Fall MATH5472 Course Project
## Title: What if without the Cox Proportional Hazard Model
## Author: Ran Liu
## Abstract
Time-to-event analysis, central to clinical trials, epidemiology, and reliability engineering, long suffered from the inability to rigorously adjust for covariates in the presence of right-censoring without strong parametric assumptions. Sir David Cox's 1972 proportional hazards model resolved this critical gap through its semi-parametric formulation and innovative partial likelihood, enabling flexible estimation of covariate effects on the hazard function while leaving the baseline hazard unspecified. This essay explores the historical necessity of the Cox model, details its mathematical foundations—including the rank-based justification of the partial likelihood and its asymptotic properties—demonstrates its interpretability, robustness, and near-parametric efficiency through examples and simulations, and surveys key competitors. Despite five decades of methodological advances, the model's enduring dominance in regulatory submissions and clinical research underscores its exceptional balance of practicality and rigor; a counterfactual examination reveals that its absence would have profoundly delayed evidence-based progress in medicine and beyond.

## Contents

Experiments.ipynb: Jupyter notebook with all R code and analyses.
Five generated PNG figures (1–5) from the report.

## Requirements
R packages: <code>survival</code>, <code>broom</code>, <code>ggplot2</code>, <code>dplyr</code>, <code>TH.data</code>, <code>flexsurv</code>, <code>patchwork</code>, <code>reshape2</code>.

Install:

```{r}
install.packages(c("survival", "broom", "ggplot2", "dplyr", "TH.data", 
                   "flexsurv", "patchwork", "reshape2"))
```
