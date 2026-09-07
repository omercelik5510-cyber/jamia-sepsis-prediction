# JAMIA Sepsis Transportability

Reproducible source code, analysis workflow, figures, and tables for the sepsis model transportability study.

## Study overview

This study evaluates the transportability of machine-learning models for sepsis prediction across distinct data environments, with emphasis on discrimination, calibration, model degradation, recalibration, recoverability, clinical utility, and subgroup performance.

## Main analysis

The complete analysis workflow is provided in:

`Sepsis_Transportability_Q1_FINAL.ipynb`

The notebook includes:

- Data preprocessing and cohort preparation
- Logistic Regression (LR)
- Histogram-based Gradient Boosting (HGB)
- Temporal HGB (HGB-T)
- Internal and external performance evaluation
- Calibration assessment
- Recalibration and recoverability analyses
- Decision-curve analysis
- Subgroup analyses
- Robustness and sensitivity analyses

## Repository structure

- `Sepsis_Transportability_Q1_FINAL.ipynb` — complete analysis notebook
- `requirements.txt` — Python dependencies
- `results/figures/` — final manuscript figures
- `results/tables/` — final and supplementary tables
- `LICENSE` — Apache License 2.0

## Data

This study uses the PhysioNet/Computing in Cardiology Challenge 2019 sepsis dataset.

Raw patient-level data are not redistributed in this repository. Users should obtain the source data separately and follow the directory structure expected by the analysis notebook.

## Reproducing the analysis

1. Download or clone this repository.
2. Install the packages listed in `requirements.txt`.
3. Obtain the PhysioNet Challenge 2019 dataset.
4. Place Set A and Set B in the directory structure expected by the notebook.
5. Open `Sepsis_Transportability_Q1_FINAL.ipynb`.
6. Run the notebook sequentially from beginning to end.

Generated manuscript figures and tables are available in the `results/` directory.

## Software environment

Analyses were performed using Python 3.14.7.

Key package versions are listed in `requirements.txt`.

## Reproducibility

Random seeds and analysis settings are specified within the notebook to support reproducibility of the reported analyses.

## License

This repository is distributed under the Apache License 2.0.
