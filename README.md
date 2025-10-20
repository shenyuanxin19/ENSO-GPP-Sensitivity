# ENSO-GPP-Sensitivity

## The goal

This study investigates how the **El Niño-Southern Oscillation (ENSO)** affects the interannual variability of tropical terrestrial carbon flux (**GPP**). Specifically, we aim to understand if **solar radiation management (SRM)** geoengineering can effectively reduce the sensitivity of terrestrial ecosystems to ENSO under high-CO₂ conditions. We hypothesize that geoengineering will significantly reduce ENSO's negative impact on tropical ecosystems by controlling temperature increases caused by elevated CO₂ levels.

## Data sources

We use climate simulation data from the **Canadian Earth System Model (CanESM5)**, provided by **CMIP6** and **GeoMIP**, under three climate scenarios:

1) **piControl** (pre-industrial baseline)
2) **abrupt-4×CO₂** (high-CO₂ warming scenario)
3) **G1** (geoengineering scenario with SRM cooling)

The variables analyzed include:

1. **Sea Surface Temperature (tos)**
https://esgf.ceda.ac.uk/thredds/fileServer/esg_cmip6/CMIP6/CMIP/CCCma/CanESM5/abrupt-4xCO2/r1i1p1f1/Omon/tos/gn/v20190429/tos_Omon_CanESM5_abrupt-4xCO2_r1i1p1f1_gn_185001-200012.nc
https://esgf.ceda.ac.uk/thredds/fileServer/esg_cmip6/CMIP6/CMIP/CCCma/CanESM5/G1/r1i1p2f1/Omon/tos/gn/v20190429/tos_Omon_CanESM5_piControl_r1i1p2f1_gn_555001-560012.nc
https://esgf.ceda.ac.uk/thredds/fileServer/esg_cmip6/CMIP6/CMIP/CCCma/CanESM5/G1/r1i1p2f1/Omon/tos/gn/v20190429/tos_Omon_CanESM5_piControl_r1i1p2f1_gn_555001-560012.nc
3. **Gross Primary Productivity (gpp)**
http://esgf3.dkrz.de/thredds/fileServer/cmip6/CMIP/CCCma/CanESM5/abrupt-4xCO2/r1i1p2f1/Lmon/gpp/gn/v20190429/gpp_Lmon_CanESM5_abrupt-4xCO2_r1i1p2f1_gn_185001-200012.nc
http://esgf3.dkrz.de/thredds/fileServer/cmip6/GeoMIP/CCCma/CanESM5/G1/r1i1p2f1/Lmon/gpp/gn/v20190429/gpp_Lmon_CanESM5_G1_r1i1p2f1_gn_185001-194912.nc
http://esgf3.dkrz.de/thredds/fileServer/cmip6/CMIP/CCCma/CanESM5/piControl/r1i1p1f1/Lmon/gpp/gn/v20190429/gpp_Lmon_CanESM5_piControl_r1i1p1f1_gn_520101-540012.nc
5. **Precipitation (pr)**
https://esgf.ceda.ac.uk/thredds/fileServer/esg_cmip6/CMIP6/CMIP/CCCma/CanESM5/abrupt-4xCO2/r1i1p2f1/Amon/pr/gn/v20190429/pr_Amon_CanESM5_abrupt-4xCO2_r1i1p2f1_gn_185001-200012.nc
https://esgf.ceda.ac.uk/thredds/fileServer/esg_cmip6/CMIP6/GeoMIP/CCCma/CanESM5/G1/r1i1p2f1/Amon/pr/gn/v20190429/pr_Amon_CanESM5_G1_r1i1p2f1_gn_185001-194912.nc
7. **Near-surface air temperature (tas)**
https://esgf.ceda.ac.uk/thredds/fileServer/esg_cmip6/CMIP6/CMIP/CCCma/CanESM5/abrupt-4xCO2/r1i1p2f1/Amon/tas/gn/v20190429/tas_Amon_CanESM5_abrupt-4xCO2_r1i1p2f1_gn_185001-200012.nc
https://esgf.ceda.ac.uk/thredds/fileServer/esg_cmip6/CMIP6/GeoMIP/CCCma/CanESM5/G1/r1i1p2f1/Amon/tas/gn/v20190429/tas_Amon_CanESM5_G1_r1i1p2f1_gn_185001-194912.nc

**Data access link:** [https://aims2.llnl.gov/search](https://aims2.llnl.gov/search)

## Planned analysis

1. Calculate and visualize **ENSO indices** (DJF Niño3.4 SST anomalies) and annual variations of tropical terrestrial carbon flux (**GPP**), comparing their variability across three climate scenarios (piControl, abrupt-4×CO₂, and G1).

2. Quantify the **sensitivity of GPP to ENSO events** using linear regression, identifying differences in ENSO–GPP relationships among the three scenarios.

3. Conduct **spatial distribution and attribution analyses** to identify regional differences in ENSO–GPP sensitivity and examine underlying drivers (**temperature and precipitation**) responsible for changes in sensitivity under the geoengineering scenario (SRM).
