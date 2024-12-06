# PPOL 6805 / DSAN 6750 Final Project:
## Spatial Analysis of Fatal Car Accidents in Montana

# Spatial Analysis of Fatal Car Accidents in Montana 

This project investigates the spatial distribution of fatal car accidents in Montana, with a focus on comparing patterns within reservation and non-reservation areas. Using spatial data science techniques, the analysis identifies clustering patterns, tests for spatial randomness, and quantifies spatial autocorrelation to uncover insights into accident distribution.  

## Key Features  
- **Data Sources**:  
  - Montana Reservations and state boundaries from [Montana Spatial Data Infrastructure (MSDI)](https://msl.mt.gov/geoinfo/msdi/administrative_boundaries/).  
  - Fatal car accident data from the [Fatality Analysis Reporting System (FARS)](https://www.nhtsa.gov/crash-data-systems/fatality-analysis-reporting-system).  
- **Exploratory Data Analysis (EDA)**: Visualizing and summarizing accident patterns across Montana.  
- **Monte Carlo Simulation**: Testing spatial randomness of accident patterns on reservations.  
- **Moran’s I Analysis**: Measuring spatial autocorrelation of accidents within and outside reservations.  
- **Visualization**: Mapping accident densities, clustering patterns, and tessellations to interpret results.  

## Findings  
- Fatal car accidents exhibit significant spatial clustering on reservations.  
- Off-reservation accident patterns are more dispersed, with weaker spatial clustering.  
- The road system likely influences spatial patterns, suggesting the need for a refined observation window in future analyses.  

## Future Work  
- Integrate additional variables like road conditions and traffic volume.  
- Analyze temporal trends in accident distributions.  
- Use Montana’s road network as the primary observation window for greater precision.  