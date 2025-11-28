# ATMS-523-Final-Project
This repository encompasses the materials required for the Module 8 Project Submission. 

## Title
ENSO and the Carbon Cycle: Linking Atmospheric CO₂ Variability to Sea Surface Temperature Anomalies Using Reanalysis Data

## Research Objectives
The goal of this project is to investigate how large-scale climate variability associated with ENSO influences atmospheric CO₂ variability. I will (1) compute deseasonalized CO₂ anomalies and identify their leading modes of variability using EOF analysis, and (2) relate those CO₂ modes to sea surface temperature (SST) anomalies and an ENSO index. The broader objective is to quantify the strength and spatial pattern of these relationships.

## Datasets
Primary CO₂ dataset: Copernicus Atmosphere Monitoring Service (CAMS) global greenhouse gas reanalysis (EGG4), which provides global fields of atmospheric CO₂ at regular time intervals from 2003 onward. 
- Source: CAMS EGG4 greenhouse gas reanalysis Atmosphere Data Store+1
- Literature/reference: Agustí-Panareda et al. 2023, The CAMS greenhouse gas reanalysis from 2003 to 2020, Atmospheric Chemistry and Physics, DOI: 10.5194/acp-23-3829-2023. ACP

Climate / ENSO-related dataset: ERA5 monthly-averaged reanalysis on single levels for sea surface temperature (SST) and 2 m air temperature from 1979–present. For consistency with CO₂ I will subset to 2003–2020.
- Source: ERA5 monthly averaged data on single levels from the Copernicus Climate Data Store. 
- Example reference DOI for ERA5 monthly means: 10.5065/D63B5XW1 (ERA5 monthly reanalysis via NCAR GDEX)

## Domain and Resolution
- Spatial domain: 60° S to 60° N, global longitude (0–360°)
- Spatial resolution: ~1° or 0.75°, depending on what I download
- Temporal resolution: monthly means
- Period: 2003–2020 (~18 years, ~216 monthly time steps)
