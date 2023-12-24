# BDGRN
# Using Bayesian correlations to infer gene regulatory network

## Data
We provide all datasets used in our paper, including simulated and experimental data. We also provide an example datasets here(`/BDGRN/data/example`).

## Quick Start
You can start with `example.R`, which can directly used our algorithm to predict gene association on the example datasets, its outputs are AUPRC/AUROC ratios and EPR (early precision ratio).

## Compute AUPRC/AUROC ratio
- If you want to take advantage of our BDGRN to compute AUPRC/AUROC/EP ratio, you can run `example.R`.
- In addition, the specific calculation function is defined in `computer.R`.
- The `density.csv` is density of different network in `/BDGRN/data/`






