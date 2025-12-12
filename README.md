# ATMS-523-Final-Project
This repository encompasses the materials required for the Module 8 Project Submission. 

## Title
ENSO and the Carbon Cycle: Linking Atmospheric CO2 Variability to Sea Surface Temperature Anomalies Using Reanalysis Data

## Research Objectives
The goal of this project is to investigate how large-scale climate variability associated with ENSO influences atmospheric CO2 variability. I will (1) compute deseasonalized CO2 anomalies and identify their leading modes of variability using EOF analysis, and (2) relate those CO2 modes to sea surface temperature (SST) anomalies and an ENSO index. The broader objective is to quantify the strength and spatial pattern of these relationships.

## Datasets
Primary CO2 dataset: Copernicus Atmosphere Monitoring Service (CAMS) global greenhouse gas reanalysis (EGG4), which provides global fields of atmospheric CO₂ at regular time intervals from 2003 onward. 
- Source: CAMS EGG4 greenhouse gas reanalysis Atmosphere Data Store
- Literature/reference: Agustí-Panareda et al. 2023, The CAMS greenhouse gas reanalysis from 2003 to 2020, Atmospheric Chemistry and Physics, DOI: 10.5194/acp-23-3829-2023. ACP

Climate / ENSO-related dataset: ERA5 monthly-averaged reanalysis on single levels for sea surface temperature (SST) and 2m air temperature from 1979–present. For consistency with CO2 I will subset to 2003–2020.
- Source: ERA5 monthly averaged data on single levels from the Copernicus Climate Data Store. 
- Reference DOI for ERA5 monthly means: 10.5065/D63B5XW1 (ERA5 monthly reanalysis via NCAR GDEX)

## Domain and Resolution
- Spatial domain: 60° S to 60° N, subset longitude to Pacific Basin (due to resource limitations)
- Temporal resolution: monthly means
- Period: 2003–2020 (~18 years, ~216 monthly time steps)

## References and Appropriate Literature
- Chatterjee et al. (2017), Influence of El Niño on atmospheric CO₂ over the tropical Pacific Ocean, DOI: 10.1126/science.aam5776
- Wang, W., et al. (2013), Variations in atmospheric CO₂ growth rates controlled by tropical temperature, DOI: https://doi.org/10.1038/ngeo1711
- Hersbach, H., et al. (2020), The ERA5 global reanalysis, Quarterly Journal of the Royal Meteorological Society, 146, 1999–2049, DOI: https://doi.org/10.1002/qj.3803
