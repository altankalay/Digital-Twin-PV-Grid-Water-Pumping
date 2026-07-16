# Digital-Twin-PV-Grid-Water-Pumping

## Supporting Materials for the Manuscript

**Title**

**Digital Twin Modelling of PV-Grid Water Pumping Using NeuralProphet and MATLAB/Simulink**

This repository provides the datasets, source codes, MATLAB/Simulink models, NeuralProphet forecasting scripts, workflow documentation, and supporting materials associated with the above manuscript submitted to **Digital Discovery (Royal Society of Chemistry)**.

---

# Repository Contents

| File / Folder | Description |
|---------------|-------------|
| `scada1.xlsx` | Processed SCADA dataset used for model development and validation |
| `PV-Design-MATLABcode/` | MATLAB scripts for PV system modelling and analysis |
| `NeuralProphet/` | NeuralProphet forecasting scripts used for motor energy demand prediction |
| `Motor_Tuketimi_Temperature_Based.numbers` | Motor energy consumption dataset |
| `demand_to_torque_workflow.svg.pdf` | Demand-to-Torque Transformation (DTT) workflow |
| `matlabcurve*.fig` | MATLAB figure files used in the manuscript |
| `matlabfib*.fig` | Supporting MATLAB figure files |
| `simulinkmodel.slx` | MATLAB/Simulink digital twin model *(if included)* |
| `README.md` | Repository documentation |

---

# Study Overview

This repository accompanies a Digital Twin framework developed for a PV-grid hybrid water pumping system.

The proposed methodology integrates:

- NeuralProphet-based motor energy demand forecasting
- Demand-to-Torque Transformation (DTT)
- MATLAB/Simulink digital twin modelling
- Three-phase induction motor simulation
- PV system modelling
- Processed SCADA measurements for validation

The repository enables independent verification and reuse of the computational workflow presented in the manuscript.

---

# Computational Workflow

The implemented workflow consists of the following stages:

1. SCADA data preprocessing
2. NeuralProphet model training
3. Hourly motor energy demand forecasting
4. Demand-to-Torque Transformation (DTT)
5. MATLAB/Simulink digital twin simulation
6. Performance evaluation
7. Figure generation

---

# Software Requirements

- MATLAB R2025b
- Simulink
- Simscape Electrical
- Python 3.x
- NeuralProphet
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

# Repository Version

**Current Release**

Version 1.0

Zenodo DOI

https://doi.org/10.5281/zenodo.21396015

GitHub Repository

https://github.com/altankalay/Digital-Twin-PV-Grid-Water-Pumping

---

# Data Availability

All processed datasets, MATLAB scripts, NeuralProphet source codes, workflow documentation, MATLAB figure files, and supporting materials required to reproduce the analyses presented in the manuscript are openly available in this repository and permanently archived on Zenodo.

---

# Reproducibility

The repository contains all computational resources required to reproduce the forecasting and simulation workflow reported in the manuscript, including:

- Processed SCADA dataset
- NeuralProphet forecasting code
- MATLAB scripts
- Simulink model
- Demand-to-Torque Transformation workflow
- Supporting figures

---

# Citation

If you use these materials, please cite both the associated manuscript and the Zenodo archive.

---

# Authors

**Ceyhun Kapucu**
**Altan Kalay**

Muğla Sıtkı Koçman University

Türkiye
