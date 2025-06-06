# 🌥️ Master's Thesis – Large-Eddy Simulations of Stratocumulus Clouds at the Chilean Coast

**Author**: Alexander Pschera  
**Institution**: University of Cologne  
**Supervisors**: Prof. Dr. Ulrich Löhnert & Dr. Jan Schween  
**Date**: November 2024  

---

## Project Overview

This repository contains Jupyter notebooks and scripts from my Master’s thesis in meteorology. The thesis investigates the representation of stratocumulus clouds in two large-eddy simulation (LES) models – ICON-LES and UCLA-LES – using observational data from Iquique, Chile.

Stratocumulus clouds significantly impact Earth’s radiation budget. However, weather and climate models still struggle to simulate their structure and variability accurately. This project evaluates how well the ICON and UCLA models reproduce cloud properties such as cloud top height, liquid water path, and boundary layer depth.

Sensitivity studies on various model parameters (e.g. sea surface temperature, vertical resolution, turbulence parameters) are conducted to understand discrepancies between model outputs and microwave radiometer / Cloudnet observations.

---

## Contents

| Notebook | Description |
|----------|-------------|
| `00_Bulk_Richardson_IQQ_NEW_20240214.ipynb` | Computes bulk Richardson numbers throughout the STBL from microwave radiometer data, airplane  and doppler lidar measurements|
| `01_Cloudnet_stuff.ipynb` | Compares cloud properties (especially cloud base height, cloud top height and cloud thickness from ICON LES to Cloudnet (Illingworth et al., 2015).|
| `02_Further_LWP_statistics.ipynb` | Analyzes liquid water path statistics from ICON-LES, UCLA-LES and microwave radiometer|
| `05_Evaluate_divergence_runs.ipynb` | Investigates divergence parameters within UCLA-LES and its effect on ABL-height development over time|
| `08_Hellinger_distance_from_IQQ...` | Applies distance metrics to model LWPs to find out how representative the site at Iquique is for the ICON model domain |
| `10_Sensitivity_study_SST_and_other.ipynb` | Compares SST and turbulence parameter sensitivity |
| ...and many more | See file names for topic-specific work |

---

## Key Topics

- Stratocumulus-topped boundary layer (STBL)
- Model evaluation (ICON-LES)
- Data assimilation and validation with:
  - Microwave radiometer data (MWR)
  - Cloud radar, Doppler lidar, Cloudnet
- Sensitivity experiments in UCLA-LES: SST, CCN, vertical resolution, turbulence closure
- Statistical and visual analysis using Python

---

## Tools & Technologies

- **Python** (NumPy, xarray, netCDF4, pandas)
- **Jupyter Notebooks**
- **ICON-LES** and **UCLA-LES** simulation output (numerical weather models written in Fortran)
- **Cloudnet**, **MWR**, and atmospheric observational datasets

---

## Notes

- This repo reflects an academic research project and includes exploratory scripts.
- Some notebooks are experimental and not fully cleaned. The work is best understood when read together with the thesis PDF (not included here).
- Model data not provided here due to size limitations.

---

## Contact

If you're interested in collaborating or want to learn more, feel free to reach out:  
apscher1@uni-koeln.de
