# CAPS Study

## Title

Factors associated with chronic opioid use in cancer survivors:
secondary analysis of the CAPS cohort.

## Authors

Nicolas Kerckhove
...

## Description

This repository contains the R code used for the statistical analyses
presented in the manuscript.

Analyses include

- Data preprocessing
- Correlation analyses
- Univariate analyses
- Logistic regression
- Cluster analysis (HCPC)
- Propensity Score Matching
- Mediation analyses
- E-value sensitivity analyses

## Dataset

The original dataset is not publicly available because it contains
patient-level health data.

Researchers may request access from the corresponding author subject to
ethical approval.

## Requirements

R >= 4.4

Packages are listed in DESCRIPTION and renv.lock.

## Running the analyses

Run the scripts in the following order

01_data_preparation.R

02_univariate_analysis.R

03_logistic_models.R

04_clustering.R

05_psm.R

06_mediation.R

Outputs are automatically generated inside the output folder.

## Citation

Please cite the associated publication.
