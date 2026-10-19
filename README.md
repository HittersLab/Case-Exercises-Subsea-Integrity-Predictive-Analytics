# Case Exercise 1: Design Envelope Construction and Visualisation

## 1. Project Overview

This project focuses on constructing and visualising the pressure–temperature (P–T) design envelope for subsea assets. It demonstrates how Python can be used to assess operating conditions against defined engineering limits, visualise operating data, and identify potential operating-envelope excursions.

The exercise uses subsea jumper data from the training case study. Where operating information was not provided, clearly labelled synthetic data and illustrative assumptions were used to demonstrate the required analysis.

## 2. Project Objectives

The objectives of this exercise are to:

1. Develop a Python function to construct a pressure–temperature design envelope, including documentation, input validation, and error handling.
2. Visualise the P–T envelope, including the simplified hydrate formation curve, wax appearance temperature (WAT) reference line, maximum allowable operating pressure (MAOP), and jumper operating points.
3. Extend the analysis to a three-parameter pressure–temperature–flow envelope and visualise operating points in three dimensions.
4. Develop a function to calculate the percentage of operating observations within the defined limits for each parameter and assess overall operating-envelope compliance.

## 3. Tools and Technologies

- Python
- Jupyter Notebook
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Git and GitHub

## 4. Project Structure

```text
Case1_Design_Envelope/
│
├── README.md
│
├── Case1_Design_Envelope.ipynb
│
└── data/
    ├── jumper_inspection_data_source_provided.csv
    ├── synthetic_jumper_flow_rates_demo.csv
    └── synthetic_hourly_operating_history_demo.csv
```

### File Descriptions

- **`README.md`** — Describes the project objectives, methodology, data assumptions, and instructions for running the notebook.
- **`Case1_Design_Envelope.ipynb`** — Contains the Markdown explanations, Python functions, engineering calculations, visualisations, synthetic data generation, and validation tests for all four assessment questions.
- **`jumper_inspection_data_source_provided.csv`** — Contains the jumper inspection and operating data used in the exercise, based on the supplied training dataset.
- **`synthetic_jumper_flow_rates_demo.csv`** — Contains illustrative synthetic flow-rate values used to extend the analysis to three parameters.
- **`synthetic_hourly_operating_history_demo.csv`** — Contains synthetic hourly operating observations used to demonstrate operating-time compliance calculations.

*Note: The assessment questions are sections within the Jupyter Notebook, not separate files or folders. Confirm that the CSV filenames and locations match the files actually committed to the repository.*

## 5. Methodology

### Question 1: Pressure–Temperature Envelope Construction

A Python function named `pressure_temperature_envelope()` defines the pressure and temperature limits for the simplified subsea operating envelope. The function includes documentation, input validation, and error handling to support reliable calculations.

### Question 2: Two-Dimensional P–T Envelope Visualisation

A two-dimensional plot displays the pressure–temperature envelope and the six jumper operating points. The visualisation includes the simplified hydrate-temperature curve, a temperature safety offset, an illustrative WAT reference line, pressure boundaries, and labelled jumper operating points.

### Question 3: Three-Parameter P–T–Flow Envelope Analysis

The analysis is extended to include flow rate alongside pressure and temperature. A three-dimensional scatter plot displays the operating points and distinguishes those classified as within or outside the defined limits.

### Question 4: Operating-Time Compliance Assessment

A Python function evaluates operating observations and calculates the percentage of observations within the defined limits for each monitored parameter. It also reports combined compliance across the selected parameters.

## 6. Data Sources and Engineering Assumptions

The supplied jumper dataset includes six records with operating pressure, temperature, water cut, original wall thickness, current wall thickness, and corrosion-rate information.

Additional flow-rate values and hourly operating observations are synthetic data generated for this educational exercise. They are not actual subsea field measurements.

A WAT value of **35°C** is used as an illustrative assumption for visualisation. It is not a confirmed field measurement.

The simplified hydrate-temperature equation follows the training exercise. The resulting envelope is an educational model and must not be interpreted as a validated engineering design envelope.

## 7. How to Run the Notebook

1. Open the project repository on GitHub.
2. Open `Case1_Design_Envelope.ipynb`.
3. Open the notebook in Google Colab or a local Jupyter Notebook environment.
4. Run the notebook cells sequentially, starting with the library imports and data setup.
5. Ensure the required CSV files are available at the file paths used by the notebook.

Install the required Python libraries if they are not already available:

```bash
pip install pandas numpy matplotlib jupyter
```

## 8. Expected Outputs

The notebook is designed to produce:

- A pressure–temperature envelope generated using Python.
- A two-dimensional P–T plot showing the operating envelope and jumper operating points.
- A three-dimensional P–T–flow visualisation.
- Operating-point classifications based on the defined limits.
- Parameter-level and combined operating-time compliance percentages.
- Validation tests demonstrating the behaviour of the implemented functions.

Actual outputs depend on successfully running the notebook and its associated data cells.

## 9. Key Learning Outcomes

This exercise demonstrates how Python can be applied to subsea engineering analysis, operating-envelope monitoring, engineering data visualisation, and basic operating-compliance assessment.

It also reinforces the importance of input validation, clear documentation, reproducible analysis, and distinguishing supplied engineering data from synthetic data and assumptions.

## 10. Disclaimer

This project is intended for educational and training purposes only. The simplified equations, illustrative assumptions, and synthetic datasets must not be used as substitutes for approved engineering calculations, validated operating limits, or formal subsea asset integrity assessments.
