# Case 2: Corrosion Rate Prediction and Remaining Useful Life

## Overview

This case exercise focuses on corrosion rate prediction and remaining useful life (RUL) estimation for subsea jumpers. It combines physics-based corrosion modelling, synthetic SCADA data generation, feature engineering, and engineering data visualisation.

## Objectives

- Implement the de Waard–Milliams corrosion rate model and develop unit tests.
- Generate a synthetic ten-year SCADA dataset with hourly readings and realistic illustrative operating parameters.
- Apply a `PhysicsFeaturePipeline` to the synthetic data.
- Calculate monthly average corrosion rates.
- Estimate remaining useful life for the six subsea jumpers provided in the case study.
- Visualise remaining useful life against corrosion rate using colour-coded risk classifications.

## Methodology

The analysis is organised into four main stages:

1. **Corrosion modelling:** Implement the de Waard–Milliams model in Python and test its behaviour.
2. **Synthetic SCADA data generation:** Generate hourly operating data over ten years for the six jumpers.
3. **Physics-based feature engineering:** Calculate corrosion-related features and monthly average corrosion rates.
4. **Remaining useful life estimation:** Calculate estimated RUL, assign illustrative risk categories, and visualise the results.

## Tools and Libraries

- Python
- Jupyter Notebook / Google Colab
- NumPy
- pandas
- Matplotlib
- unittest

## Expected Deliverables

- A Jupyter notebook containing the corrosion model, synthetic data generation, feature pipeline, calculations, tests, and visualisations.
- An enriched CSV dataset containing the relevant corrosion-related features.
- Monthly average corrosion rate results.
- A CSV file containing the estimated RUL and risk classification for each jumper.

## Data and Assumptions

The SCADA dataset is synthetic and intended for educational purposes. It does not represent verified operational records from the Usan field.

Any assumed operating ranges, corrosion parameters, minimum allowable wall thicknesses, and risk classification thresholds must be documented in the notebook. Engineering calculations should be validated against the applicable course material and approved engineering requirements.

## How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Install or import the required Python libraries.
3. Run the notebook cells in sequence.
4. Review the model tests, enriched dataset, monthly corrosion results, RUL calculations, and visualisations.

## Engineering Disclaimer

The corrosion predictions and remaining useful life estimates are educational outputs. They must not be used for operational decisions without validation against appropriate inspection data, engineering standards, and approved asset-specific limits.
