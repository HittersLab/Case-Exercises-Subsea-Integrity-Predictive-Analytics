# Case Exercise 1: Design Envelope Construction and Visualisation

## Project Overview

This project focuses on constructing and visualising a pressure–temperature (P–T) design envelope for subsea asset integrity using Python.

The objective is to understand how operating conditions can be assessed against design limits to support safe and reliable subsea production operations.

## Objectives

1. Implement a pressure temperature design envelope function.
2. Visualise the safe operating region, hydrate formation boundary, wax appearance temperature (WAT) line, and maximum allowable operating pressure (MAOP).
3. Extend the analysis to a 3 parameter pressure temperature flow rate envelope.
4. Calculate the percentage of operating records that remain within specified design limits.

## Tools and Technologies

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Git and GitHub

## Project Structure

```text
Case1_Design_Envelope/
├── README.md
├── Case1_Design_Envelope.ipynb
└── data/
    └── jumper_operating_data.csv
```

## Data

The project requires the six jumper operating points referenced in the training material's Table 2.9 and the applicable WAT value. These values must be entered from the source material before completing the corresponding visualisations.

## Methodology

The analysis will use documented Python functions, validation checks, visualisations, and operating-envelope classification to assess subsea operating conditions.

## Important Note

The simplified hydrate relationship used in this educational exercise is not a substitute for a validated engineering flow-assurance model. Actual operational decisions must use approved engineering limits and appropriate specialist analysis.
