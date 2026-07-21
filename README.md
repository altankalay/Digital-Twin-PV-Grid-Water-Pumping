# Digital Twin PV-Grid Water Pumping

Supporting materials for the manuscript:

**Digital Twin Modelling of PV-Grid Water Pumping Using NeuralProphet and MATLAB/Simulink**

This repository provides the MATLAB/Simulink models, NeuralProphet forecasting codes, supporting datasets, archived MATLAB figure files, SCADA measurements, workflow diagrams, and documentation used in the development and evaluation of a Digital Twin framework for a photovoltaic-grid water pumping system.

---

# Repository Contents

## NeuralProphet-Optuna/

Python implementation of NeuralProphet forecasting models together with Optuna-based hyperparameter optimization.

Forecasted variables include:

- Solar irradiance
- Ambient temperature
- Motor energy demand

---

## PV-Design-MATLABcode/

MATLAB scripts used for:

- PV system modelling
- Electrical analysis
- Figure generation
- MATLAB/Simulink simulations

---

## Supporting MATLAB Datasets

### PowerSystem2024_Dataset.mat

MATLAB dataset containing hourly electrical variables extracted for analysis and visualization.

Variables include:

- Voltage
- Current
- Active Power
- Reactive Power
- Power Factor

Example:

```matlab
load('PowerSystem2024_Dataset.mat')
```

---

### co10_hourly_2024_reconstructed.mat

Hourly reconstructed dataset generated from the archived **co10.fig** MATLAB figure.

The file contains the reconstructed hourly data used for reproducing the corresponding figure and supporting numerical analysis.

Example:

```matlab
load('co10_hourly_2024_reconstructed.mat')
```

---

## MATLAB Figure Files

Archived MATLAB figure files are included for reproducibility.

Current figure files include:

- co10.fig
- matlabcurve1.fig
- matlabcurve5.fig
- matlabfib3.fig

These files can be opened directly in MATLAB.

---

## Experimental Data

### scada1.xlsx

Experimental SCADA measurements collected from the water pumping system.

These measurements were used for comparison and validation of the MATLAB/Simulink simulation results.

---

## MATLAB/Simulink Resources

The repository contains MATLAB and Simulink resources used throughout the study, including:

- PV system modelling
- Dynamic simulation
- Electrical performance evaluation
- Digital Twin implementation
- Figure generation

Additional documentation:

- simulinkmodeltumsystem.pdf

---

## Demand-to-Torque Workflow

The repository includes the complete Demand-to-Torque (DTT) workflow describing the conversion of forecasted motor energy demand into mechanical load torque for MATLAB/Simulink implementation.

Workflow diagram:

- demand_to_torque_workflow.svg

---

## Simulation Figures

Supporting simulation figures are included to facilitate interpretation of the presented results.

Example files:

- sim112.png

---

# Software

The study was developed using:

- MATLAB R2025b
- Simulink
- Python
- NeuralProphet
- Optuna

---

# Repository Purpose

This repository is intended to support transparency and reproducibility by providing the numerical datasets, forecasting codes, simulation resources, archived MATLAB figures, workflow documentation, and supporting files associated with the manuscript.

---

# Citation

If you use this repository in your research, please cite the associated manuscript.

---

# Contact

**Altan Kalay**

GitHub:

https://github.com/altankalay
