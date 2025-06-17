# AMRanalysis
R script for modelling resistance indicators in Madagascar
# Drug Resistance in Salmonella Typhi,iNTS,Shigella and Klebsiella isolates.

This repository contains an R script (`finalanalysisl.R`) for a logistic regression analysis on factors associated with drug resistance in *Salmonella Typhi, iNTS,Shigella and Klebsiella isolates.

## Script Overview
- Filters blood culture-positive cases of Salmonella Typhi, iNTS,Shigella and Klebsiella isolates.
- Runs a logistic regression model using:
  - Age
  - Sex
  - Premedication
  - Pregnancy status
  - Pandemic period (not relevant at this point but will be useful for SETAplus)
  - Comorbidities

## Requirements
- R
- Packages: `dplyr`, `ggplot2` (if plotting), `readxl`, `purrr`, `tidyr`, `lubridate`

## How to Use
1. Clone the repo or download the script.
2. Load your dataset as `analytical_dataset`.
3. Run `finalanalysisl.R`.

> Note: Data is not included due to confidentiality.
