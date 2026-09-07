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
- AUROC and related discrimination metrics
- Calibration assessment
- Recalibration analyses
- Recoverability analyses
- Decision-curve analysis
- Subgroup analyses
- Robustness and sensitivity analyses

## Repository structure

```text
jamia-sepsis-prediction/
│
├── Sepsis_Transportability_Q1_FINAL.ipynb
├── requirements.txt
├── README.md
├── LICENSE
│
└── results/
    ├── figures/
    │   ├── Figure_1_Recoverability_FINAL.png
    │   ├── Figure_2_Recalibration_Sample_Size_FINAL.png
    │   ├── Figure_3_Decision_Curves_FINAL.png
    │   └── Figure_4_Subgroup_Forest_FINAL.png
    │
    └── tables/
        ├── q1_tables_FINAL.xlsx
        └── JAMIA_Sepsis_Transportability_Supplementary_Tables_S1-S11.docx
Data

This study uses the PhysioNet/Computing in Cardiology Challenge 2019 sepsis dataset.

Raw patient-level data are not redistributed in this repository. Users should obtain the source data separately and follow the directory structure expected by the analysis notebook.

Reproducing the analysis
Download or clone this repository.
Install the required Python packages:
pip install -r requirements.txt
Obtain the PhysioNet Challenge 2019 dataset.
Place the Set A and Set B data in the directory structure expected by the notebook.
Open:
Sepsis_Transportability_Q1_FINAL.ipynb
Run the notebook sequentially from beginning to end.

Generated manuscript figures and tables are available in the results/ directory.

Software environment

Analyses were performed using Python 3.14.7.

Key package versions are listed in requirements.txt.

Reproducibility

Random seeds and analysis settings are specified within the notebook to support reproducibility of the reported analyses.

License

This repository is distributed under the Apache License 2.0.


Sonra:

**Commit changes...**

Commit mesajı:

```text
Finalize README and reproducibility instructions
