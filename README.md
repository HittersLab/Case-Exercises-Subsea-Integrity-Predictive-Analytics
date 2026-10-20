# Case Exercises: Subsea Integrity Predictive Analytics

## Project Overview

This repository contains practical engineering case exercises focused on subsea asset integrity, corrosion prediction, remaining useful life estimation, Failure Mode, Effects and Criticality Analysis (FMECA), and predictive analytics.

The project combines subsea engineering principles with Python programming, data analysis, physics-based modelling, and visualisation. Each case is organised in a separate folder containing its Jupyter notebook and relevant supporting files.

## Project Objectives

- Apply engineering principles to subsea asset integrity challenges.
- Develop Python functions for engineering calculations and physics-based models.
- Generate and analyse synthetic operational datasets.
- Estimate corrosion rates and remaining useful life (RUL).
- Identify potential subsea equipment failure modes and assess their risks.
- Explore how engineering parameters can support machine learning feature engineering.
- Develop practical, reproducible engineering analysis workflows.

## Case Exercises

### Case 1: Design Envelope Construction and Visualisation

**Folder:** `Case1_Design_Envelope/`

Focuses on subsea operating envelopes and the monitoring of pressure and temperature conditions against defined operating limits.

Key activities:
- Implement a pressure–temperature design envelope function.
- Visualise operating conditions and relevant engineering boundaries.
- Extend the visualisation to include flow-related operating conditions.
- Assess the proportion of operating time spent within the defined envelope.

### Case 2: Corrosion Rate Prediction and Remaining Useful Life

**Folder:** `Case2_Corrosion_RUL/`

Focuses on corrosion modelling, synthetic SCADA data analysis, and the estimation of remaining useful life for subsea jumpers.

Key activities:
- Implement the de Waard–Milliams corrosion rate model and unit tests.
- Generate a synthetic ten-year hourly operational dataset.
- Apply a physics-based feature pipeline and calculate monthly average corrosion rates.
- Estimate jumper remaining useful life and visualise corrosion-related risk classifications.

### Case 3: FMECA and Feature Mapping

**Folder:** `Case3_FMECA_Feature_Mapping/`

Focuses on Failure Mode, Effects and Criticality Analysis for subsea Christmas trees and the mapping of engineering failure mechanisms to potential machine learning features.

Key activities:
- Develop an FMECA worksheet covering at least ten failure modes.
- Map failure modes to relevant physical parameters and proposed engineered features.
- Implement and validate at least two physics-based models against hand calculations.
- Visualise failure-mode severity, occurrence, and Risk Priority Numbers (RPNs).

## Tools and Technologies

- **Python** — engineering calculations and data processing.
- **Jupyter Notebook / Google Colab** — interactive development and documentation.
- **NumPy and pandas** — numerical computing and data analysis.
- **Matplotlib** — engineering data visualisation.
- **Git and GitHub** — version control and project documentation.

## Repository Structure

```text
Case-Exercises-Subsea-Integrity-Predictive-Analytics/
├── README.md
├── Case1_Design_Envelope/
│   ├── README.md
│   └── Case1_Design_Envelope.ipynb
├── Case2_Corrosion_RUL/
│   ├── README.md
│   └── Case2_Corrosion_RUL.ipynb
└── Case3_FMECA_Feature_Mapping/
    ├── README.md
    └── Case3_FMECA_Feature_Mapping.ipynb
```

Supporting datasets, test files, and visualisation outputs will be stored in the relevant case folders as required.

## Data and Engineering Assumptions

Synthetic datasets and illustrative assumptions may be used for educational purposes where actual operational data or approved engineering limits are unavailable. Such assumptions will be identified in the relevant notebooks.

The analyses are intended for learning and demonstration. They do not replace approved engineering design codes, asset-specific integrity assessments, or validated operational data.

## Learning Outcomes

This project supports the development of practical skills in subsea integrity engineering, Python programming, physics-based modelling, data analytics, and predictive maintenance concepts.

It also demonstrates the application of computational methods to engineering problems relevant to the energy sector.

## Author

Graduate Trainee Engineer | Energy Sector | Predictive AI and Machine Learning

