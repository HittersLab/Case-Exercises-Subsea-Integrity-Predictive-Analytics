
# Case 1: Design Envelope Construction and Visualisation

## Overview

This case exercise focuses on constructing and visualising a pressure–temperature (P–T) design envelope for subsea assets. It demonstrates how engineering operating limits can be used to assess operating conditions and support subsea asset integrity monitoring.

## Objectives

- Implement a Python function to define a pressure–temperature design envelope.
- Visualise the safe operating region and relevant engineering boundaries.
- Plot subsea jumper operating conditions against the defined envelope.
- Extend the visualisation to include flow-related operating conditions.
- Calculate the percentage of operating time that selected parameters remain within the defined envelope.

## Methodology

The analysis uses Python to define the operating envelope, evaluate operating conditions, and generate engineering visualisations. Synthetic operating data is used where necessary to demonstrate monitoring and compliance calculations.

The notebook includes:

1. Design envelope function implementation and validation.
2. Two-dimensional pressure–temperature visualisation.
3. Three-dimensional pressure–temperature–flow visualisation.
4. Operating-envelope compliance analysis using synthetic hourly data.

## Tools and Libraries

- Python
- Jupyter Notebook / Google Colab
- NumPy
- pandas
- Matplotlib

## Deliverables

- `Case1_Design_Envelope.ipynb` — Jupyter notebook containing the analysis and visualisations.
- Supporting CSV datasets generated or used by the notebook, where applicable.

## Assumptions and Limitations

Synthetic data and illustrative assumptions are used for demonstration where actual operating data or approved engineering limits are unavailable. These assumptions should be clearly identified in the notebook.

The analysis is for educational purposes and does not replace approved engineering design limits or a formal subsea integrity assessment.

## How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Install or import the required Python libraries.
3. Run the notebook cells in sequence.
4. Review the calculations, plots, and compliance results.
