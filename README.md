# Digital Twin Modelling of PV–Grid Water Pumping Using NeuralProphet and MATLAB/Simulink

This repository contains the datasets, NeuralProphet forecasting resources, MATLAB/Simulink models, archived MATLAB figures, and supporting documentation associated with the study:

> **Digital Twin Modelling of PV–Grid Water Pumping Using NeuralProphet and MATLAB/Simulink**

The proposed framework combines data-driven forecasting with a physics-based digital twin to evaluate the operation and performance of a photovoltaic-grid-connected municipal water-pumping system.

---

# Repository Structure

```
Digital-Twin-PV-Grid-Water-Pumping/
│
├── Documentation/
├── NeuralProphet/
├── PV-Design-MATLABcode/
│
├── PowerSystem2024_Dataset.mat
├── matlabcurve5_extracted_data.mat
├── co10_hourly_2024_reconstructed.mat
├── co10_hourly_2024_reconstructed.csv
├── scada1.xlsx
│
├── co10.fig
├── matlabcurve5.fig
├── matlabfib3.fig
│
├── demand_to_torque_workflow.svg
├── demand_to_torque_workflow.svg.pdf
├── simulinkmodeltumsystem.pdf
│
└── README.md
```

---

# Project Overview

This repository provides the computational resources supporting the proposed digital twin framework, including:

- NeuralProphet-based forecasting
- MATLAB/Simulink digital twin model
- PV-grid water-pumping system model
- SCADA datasets
- Supporting MATLAB datasets
- Archived MATLAB figures
- Demand-to-Torque (DTT) workflow
- Technical documentation

---

# NeuralProphet Resources

The **NeuralProphet** directory contains the complete forecasting workflow used in this study, including:

- Data preprocessing
- Feature engineering
- Time-series preparation
- NeuralProphet model configuration
- Hyperparameter optimization using Optuna
- Model training
- Validation
- Forecast generation
- Model evaluation
- Prediction outputs

These resources reproduce the forecasting stage of the proposed digital twin methodology.

---

# MATLAB/Simulink Resources

The repository includes MATLAB and Simulink resources supporting the implementation of the PV-grid water-pumping digital twin.

The simulation framework includes:

- Photovoltaic array model
- Grid connection
- Three-phase inverter
- Electrical measurement blocks
- Three-phase asynchronous machine
- Pump-load representation
- Environmental input profiles
- Electrical system outputs

---

# Supporting Datasets

The repository includes the supporting datasets used throughout the study.

- **PowerSystem2024_Dataset.mat**  
  Hourly electrical-system dataset used in the MATLAB/Simulink analysis.

- **matlabcurve5_extracted_data.mat**  
  Supporting electrical-system dataset associated with the archived MATLAB figure files.

- **co10_hourly_2024_reconstructed.mat**  
  Hourly dataset supporting the archived `co10.fig` analysis.

- **co10_hourly_2024_reconstructed.csv**  
  CSV version of the hourly dataset.

- **scada1.xlsx**  
  SCADA and environmental measurements supporting forecasting and simulation.

---

# Archived MATLAB Figures

Archived MATLAB figure files associated with the reported analyses.

- **co10.fig**
- **matlabcurve5.fig**
- **matlabfib3.fig**

---

# Demand-to-Torque Workflow

The repository includes the complete Demand-to-Torque (DTT) workflow used to convert forecasted motor-energy demand into the equivalent mechanical load required by the MATLAB/Simulink asynchronous machine model.

Supporting files:

- demand_to_torque_workflow.svg
- demand_to_torque_workflow.svg.pdf

---

# Documentation

Supporting documentation includes:

- MATLAB/Simulink model documentation
- Demand-to-Torque workflow
- Supplementary project documentation

---

# Software Requirements

## MATLAB Environment

- MATLAB R2025b
- Simulink
- Simscape Electrical

## Python Environment

| Package | Version |
|----------|----------|
| matplotlib | 3.11.1 |
| neuralprophet | 0.9.0 |
| numpy | 2.5.1 |
| optuna | 4.4.0 |
| pandas | 3.0.3 |
| pvlib | 0.13.0 |
| pytz | 2025.2 |
| scikit-learn | 1.9.0 |
| scipy | 1.18.0 |

The forecasting workflow was developed and tested using the software versions listed above.

---

# Data Availability

All supporting datasets, archived MATLAB figures, forecasting resources, and supplementary documentation associated with this work are available through this GitHub repository.

A permanent archived version is also available via Zenodo.

**DOI**

10.5281/zenodo.21420535

---

# Repository Version

**Current Release:** Version 1.3

Latest updates include:

- Supporting MATLAB datasets
- Archived MATLAB figures
- Updated NeuralProphet forecasting resources
- Demand-to-Torque workflow
- Additional project documentation

---

# Related Publication

This repository supports the manuscript:

**Digital Twin Modelling of PV–Grid Water Pumping Using NeuralProphet and MATLAB/Simulink**

The complete bibliographic information will be updated following publication.

---

# Citation

If this repository contributes to your research, please cite both the associated publication and the corresponding Zenodo repository.

---

# License

This repository is provided for academic research, verification, and reproducibility purposes.

---

# Contact

**Altan Kalay**

Muğla Sıtkı Koçman University  
Muğla, Türkiye
