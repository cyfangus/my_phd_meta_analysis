# Procedural Justice, Social Identity & Legitimacy Meta-Analysis
Author: Angus Chan
Institution: UCL Department of Security and Crime Science

## Project Overview
This repository contains the reproducible analytical pipeline for a large-scale meta-analysis of 123 studies ($N = 200,966$). The project quantifies the global correlations between procedural justice, social identity, and police legitimacy.This infrastructure was designed to handle diverse statistical reporting formats and harmonize disparate datasets into a single relational structure—mirroring the robust data management requirements of multi-site longitudinal research.

## Technical Infrastructure
This project is built using R and follows a modular design to ensure high data auditability and transparency.
- Language: R (Version 4.x)
- Key Libraries: metafor (meta-analysis), tidyverse (data cleaning), ggplot2 (visualization).
- Version Control: Git/GitHub for full pipeline history.
- Data Standards: Implements a custom coding schema to handle multi-level effect sizes and cross-study variance.

## Repository Structure
```text
├── R/                        # Modular R functions for data processing
├── main.R                    # Primary entry point to execute the full pipeline
├── meta_analysis_data.csv    # Harmonized dataset (anonymized/de-identified)
└── README.md                 # Project documentation
```

## Usage & Reproducibility
To reproduce the findings, clone this repository and run the primary script:
1. Clone the repo:

```console
git clone https://github.com/cyfangus/my_phd_meta_analysis.git
```

2. Execute Analysis: Open main.R in RStudio. The script is configured to automatically load dependencies and process the raw data in the /R directory.

## Data Governance & Open Science
Ethics: All data handling follows UCL Research Ethics and GDPR protocols.

Anonymization: Raw data has been pseudonymized and aggregated to ensure participant privacy while maintaining research utility.

Transparency: This repository serves as an Open Science archive to support the "Interoperability" and "Reusability" (FAIR) of the research findings.

## Contact
For inquiries regarding the data schema or methodological framework: Angus Chan - cyfangus@gmail.com
