# Digital-Twin-PV-Grid-Water-Pumping

## Supporting Materials for the Manuscript

### Title

**Digital Twin Modelling of PV-Grid Water Pumping Using NeuralProphet and MATLAB/Simulink**

This repository provides the processed datasets, source codes, MATLAB/Simulink modelling files, NeuralProphet forecasting scripts, workflow documentation, and supporting materials associated with the manuscript submitted to **Digital Discovery (Royal Society of Chemistry)**.

---

## Repository Contents

| File / Folder | Description |
|---|---|
| `scada1.xlsx` | Processed SCADA dataset used for model development and validation |
| `PV-Design-MATLABcode/` | MATLAB scripts and supporting files used for PV system modelling and analysis |
| `NeuralProphet-Optuna/` | NeuralProphet forecasting and Optuna-based hyperparameter optimization files |
| `demand_to_torque_workflow.svg.pdf` | Demand-to-Torque Transformation (DTT) workflow diagram |
| `simulinkmodeltumsystem.pdf` | Overview of the MATLAB/Simulink digital twin model |
| `matlabcurve1.fig` | MATLAB figure file |
| `matlabcurve5.fig` | MATLAB figure file |
| `matlabfib3.fig` | Supporting MATLAB figure file |
| `matlabfig2.fig` | Supporting MATLAB figure file |
| `README.md` | Repository documentation |

---

## Study Overview

This repository accompanies a digital twin framework developed for a PV-grid hybrid water pumping system.

The proposed methodology integrates:

- NeuralProphet-based motor energy demand forecasting
- Optuna-based hyperparameter optimization
- Demand-to-Torque Transformation (DTT)
- MATLAB/Simulink digital twin modelling
- Three-phase induction motor simulation
- PV system modelling
- Processed SCADA measurements for model development and validation

The repository is intended to support independent verification, reproducibility, and reuse of the computational workflow presented in the manuscript.

---

## Computational Workflow

The implemented workflow consists of the following stages:

1. SCADA data preparation
2. NeuralProphet model development
3. Optuna-based hyperparameter optimization
4. Hourly motor energy demand forecasting
5. Demand-to-Torque Transformation
6. MATLAB/Simulink digital twin simulation
7. Performance evaluation
8. Figure generation

---

## Software Requirements

### MATLAB Environment

- MATLAB R2025b
- Simulink
- Simscape Electrical

### Python Environment

- Python 3.x
- NeuralProphet
- Optuna

Only the software and libraries explicitly associated with the deposited workflow are listed above.

---

## Repository Version

**Current Release:** Version 1.0

**Zenodo DOI:**  
https://doi.org/10.5281/zenodo.21396015

**GitHub Repository:**  
https://github.com/altankalay/Digital-Twin-PV-Grid-Water-Pumping

---

## Data Availability

The processed datasets, MATLAB scripts, NeuralProphet and Optuna files, workflow documentation, MATLAB figure files, and supporting materials deposited in this repository are openly available through GitHub and permanently archived on Zenodo.

The repository contents correspond to the computational materials made available for the associated manuscript.

---

## Reproducibility

The repository provides the principal computational resources required to examine and reproduce the forecasting and simulation workflow reported in the manuscript, including:

- Processed SCADA data
- NeuralProphet forecasting files
- Optuna optimization files
- MATLAB scripts
- PV system modelling files
- Demand-to-Torque Transformation documentation
- MATLAB/Simulink model documentation
- Supporting MATLAB figures

Users should verify local software compatibility, file paths, and model configuration before executing the workflow.

---

## Citation

If you use the data, code, workflow, or supporting materials in this repository, please cite both:

1. The associated manuscript
2. The Zenodo archive

### Repository Citation

Kapucu, C., and Kalay, A.  
**Digital Twin Modelling of PV-Grid Water Pumping Using NeuralProphet and MATLAB/Simulink.**  
Version 1.0. Zenodo.  
https://doi.org/10.5281/zenodo.21396015

The full journal citation should be added after publication of the associated article.

---

## Authors

**Ceyhun Kapucu**  
**Altan Kalay**

Muğla Sıtkı Koçman University  
Türkiye

---

## License

No explicit software or data license is currently specified in this repository.

Reuse of the deposited materials should therefore be undertaken with appropriate citation and in accordance with the terms displayed on the corresponding Zenodo record.
