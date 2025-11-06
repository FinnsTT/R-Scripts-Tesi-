# R-Scripts-Tesi-
# Brown Hyena Population Density Analysis - Fish River Canyon

## Project Description
Spatial covariate extraction for N-Mixture models to estimate brown hyena (*Parahyaena brunnea*) population density in Fish River Canyon, Namibia.

## Data Sources
- DEM: 30m resolution
- Camera traps: 71 stations (May 2023 - June 2025)
- Spatial layers: Rivers, water points, tourist road, buildings

## Covariates Extracted
### Terrain metrics:
- Elevation (point and 1km buffer mean)
- Slope (point and 1km buffer mean)
- TRI - Terrain Ruggedness Index (point and 1km buffer mean)
- Aspect
- TPI - Topographic Position Index

### Distance metrics:
- Distance to Fish River
- Distance to Konkiep River
- Distance to water points (artificial + natural)
- Distance to tourist road
- Distance to staff buildings

## Software
- R version 4.x
- Required packages: terra, sf, dplyr, spatialEco, raster
