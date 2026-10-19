# Case Exercise 1: Design Envelope Construction and Visualisation

## 1. Project Overview

This project focuses on constructing and visualising the pressure–temperature (P–T) design envelope for subsea assets. It demonstrates how Python can support subsea integrity monitoring by comparing operating conditions against defined engineering limits and identifying potential operating excursions.

The exercise uses subsea jumper data from the training case study. Where operating information was not provided, clearly labelled synthetic data and illustrative assumptions were introduced to demonstrate the required analysis.

## 2. Project Objectives

The objectives of this exercise are to:

1. Develop a Python function to construct a pressure–temperature design envelope, including documentation, input validation, and error handling.
2. Visualise the P–T envelope, including the simplified hydrate formation curve, wax appearance temperature (WAT) reference line, maximum allowable operating pressure (MAOP), and jumper operating points.
3. Extend the analysis to a three-parameter pressure–temperature–flow envelope and visualise operating points in three dimensions.
4. Develop a function to calculate the percentage of operating observations within the defined limits for each parameter and assess overall operating-envelope compliance.

## 3. Tools and Technologies

- Python
- Jupyter Notebook
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
    ├── jumper_operating_data.csv
    ├── synthetic_flow_rate_data.csv
    └── synthetic_hourly_operating_data.csv
```

### File Descriptions

- **README.md:** Documents the project objectives, methodology, data assumptions, and instructions for running the analysis.
- **Case1_Design_Envelope.ipynb:** Contains the engineering explanations, Python functions, calculations, visualisations, synthetic data generation, and validation checks for the four assessment questions.
- **jumper_operating_data.csv:** Contains the six jumper records from the training exercise, including operating pressure, temperature, water cut, wall thickness, and corrosion-rate information.
- **synthetic_flow_rate_data.csv:** Contains illustrative synthetic flow-rate values used for the three-parameter analysis.
- **synthetic_hourly_operating_data.csv:** Contains synthetic hourly operating observations used to demonstrate the operating-time compliance calculations.

*Note: The assessment questions are sections within the Jupyter Notebook, not separate files or folders. The CSV files should be stored in the `data/` directory if the notebook uses the paths shown above.*

## 5. Methodology

### Question 1: Pressure–Temperature Envelope Construction

A Python function, `pressure_temperature_envelope()`, defines the pressure and temperature limits for the simplified subsea operating envelope. The function includes input validation and error handling to support reliable calculations.

### Question 2: Two-Dimensional P–T Visualisation

A two-dimensional plot is used to display the pressure–temperature envelope and the six jumper operating points. The visualisation includes the simplified hydrate-temperature curve, an illustrative WAT reference line, pressure boundaries, and operating points labelled by jumper identification.

### Question 3: Three-Parameter P–T–Flow Analysis

The analysis is extended to include flow rate alongside pressure and temperature. A three-dimensional scatter plot illustrates the operating points and distinguishes points classified as within or outside the defined limits.

### Question 4: Operating-Time Compliance Assessment

A Python function evaluates the operating observations and calculates the percentage of time each monitored parameter remains within its defined limits. The function also reports combined compliance across the selected parameters.

## 6. Data Sources and Engineering Assumptions

The supplied jumper dataset contains six records with pressure, temperature, water cut, original wall thickness, current wall thickness, and corrosion-rate information.

Additional flow-rate values and hourly operating observations are synthetic data generated for this educational exercise. They are not actual subsea field measurements.

A wax appearance temperature (WAT) of **35°C** is used as an illustrative assumption for the visualisation. It is not a confirmed field measurement.

The simplified hydrate-temperature equation provided in the training exercise is used for demonstration. The resulting envelope is an educational model and should not be interpreted as a validated engineering design envelope.

## 7. How to Run the Notebook

1. Open this repository on GitHub.
2. Open `Case1_Design_Envelope.ipynb`.
3. Run the notebook in Google Colab or a local Jupyter Notebook environment.
4. Execute the cells sequentially, starting with the imports and data setup.
5. Ensure the `data/` directory and required CSV files are available when executing cells that load saved datasets.

Install the required libraries in a Python environment if they are not already available:

```bash
pip install pandas numpy matplotlib jupyter
```

## 8. Expected Outputs

The notebook is designed to produce:

- A defined pressure–temperature operating envelope.
- A two-dimensional P–T plot showing the envelope and jumper operating points.
- A three-dimensional P–T–flow visualisation.
- Operating-point classifications based on the selected limits.
- Parameter-level and combined operating-time compliance percentages.
- Validation checks demonstrating the behaviour of the implemented functions.

These outputs depend on successfully running the notebook and its associated data cells.

## 9. Key Learning Outcomes

This exercise demonstrates how Python can be applied to subsea integrity analysis, engineering data visualisation, operating-envelope monitoring, and basic operating-compliance assessment.

It also reinforces the importance of input validation, clear documentation, reproducible analysis, and distinguishing supplied engineering data from synthetic data and assumptions.

## 10. Disclaimer

This project is intended for educational and training purposes only. The simplified equations, illustrative assumptions, and synthetic data must not be used as a substitute for approved engineering calculations, validated operating limits, or formal subsea asset integrity assessments.
