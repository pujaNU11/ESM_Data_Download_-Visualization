# Climate Extremes Analysis Toolkit

A Python toolkit for analyzing climate extremes using CMIP6 Earth System Model data. This repository provides tools to analyze historical (1850-2014) and future (2015-2100, SSP585 scenario) climate patterns with focus on precipitation extremes and temperature anomalies.

## Features
- Process CanESM5 model data from CMIP6
- Extract location-specific climate data globally
- Calculate extreme precipitation return levels using GEV distributions
- Compute Warm Spell Duration Index (WSDI)
- Analyze night-time temperature maxima
- Generate comparative visualizations between historical and future climates

## Applications
- Climate risk assessment
- Urban planning under climate change
- Infrastructure resilience studies
- Agricultural adaptation strategies
- Climate science education

## Technical Stack
- Data processing: xarray, numpy, pandas
- Statistical analysis: lmoments3, GEV distributions
- Visualization: matplotlib
- Dependencies: cftime and other Python packages

The repository includes Jupyter notebooks demonstrating analysis for multiple global locations, calculation of climate indices, and generation of publication-quality visualizations for communicating climate change impacts.
