# Digital Twin PV-Grid Water Pumping

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21396014.svg)](https://doi.org/10.5281/zenodo.21396014)

Supporting data, source code, and documentation for the manuscript:

> **Digital Twin Modelling of PV-Grid Water Pumping Using NeuralProphet and MATLAB/Simulink**

Submitted to **Digital Discovery (Royal Society of Chemistry)**.

---

# Overview

This repository provides the computational workflow, source code, processed dataset, and supporting documentation used for the development of a digital twin framework for a PV-grid water pumping system.

The proposed framework combines:

- NeuralProphet forecasting
- Optuna hyperparameter optimization
- MATLAB/Simulink digital twin modelling
- Demand-to-Torque (DTT) transformation
- PV system modelling
- SCADA-based validation

The repository is intended to improve transparency, reproducibility, and long-term accessibility of the research.

---

# Repository Contents

```
Digital-Twin-PV-Grid-Water-Pumping
│
├── NeuralProphet-Optuna
│      NeuralProphet forecasting and Optuna optimization source code
│
├── PV-Design-MATLABcode
│      MATLAB scripts used for PV system design
│
├── scada1.xlsx
│      Processed SCADA dataset
│
├── demand_to_torque_workflow.svg.pdf
│      Demand-to-Torque (DTT) workflow
│
├── simulinkmodeltumsystem.pdf
│      MATLAB/Simulink model documentation
│
├── matlabcurve1.fig
├── matlabcurve5.fig
├── matlabfig2.fig
├── matlabfib3.fig
│      MATLAB figure files
│
└── README.md
```

---

# Methodology

The proposed digital twin consists of the following workflow:

SCADA Data

↓

NeuralProphet Forecasting

↓

Optuna Hyperparameter Optimization

↓

Demand-to-Torque (DTT) Transformation

↓

MATLAB/Simulink Digital Twin

↓

PV-Grid Water Pumping Simulation

↓

Performance Evaluation

---

# Repository Features

- NeuralProphet forecasting model
- Optuna hyperparameter optimization
- MATLAB PV system design scripts
- Demand-to-Torque transformation methodology
- MATLAB figure files
- Processed SCADA dataset
- Simulink model documentation
- Complete workflow documentation

---

# Software Requirements

## MATLAB

- MATLAB R2025b
- Simulink
- Simscape Electrical

## Python

- Python 3.x
- NeuralProphet
- Optuna
  

---

# Repository Release

Current Release

**Version 1.1**

Current Version DOI

https://doi.org/10.5281/zenodo.21420528

Concept DOI (always resolves to the latest version)

https://doi.org/10.5281/zenodo.21396014

GitHub Repository

https://github.com/altankalay/Digital-Twin-PV-Grid-Water-Pumping

---

# Citation

If you use this repository in your research, please cite the latest archived version through Zenodo.

**Concept DOI**

https://doi.org/10.5281/zenodo.21396014

or cite the exact software version used:

**Version 1.1**

https://doi.org/10.5281/zenodo.21420528

---

# License

This repository is provided for academic and research purposes.

Please cite the associated manuscript and the Zenodo archive when using any part of this repository.

---

# Acknowledgement

The authors acknowledge the use of:

- GitHub for version control
- Zenodo for software archiving and DOI assignment
- MATLAB/Simulink for digital twin modelling
- NeuralProphet for time-series forecasting
- Optuna for hyperparameter optimization

---

# Contact

**Altan Kalay**

GitHub:

https://github.com/altankalay

Repository:

https://github.com/altankalay/Digital-Twin-PV-Grid-Water-Pumping

Zenodo:

https://doi.org/10.5281/zenodo.21396014
