## Rivers in the Sky: Exploring Wintertime Moisture Flux over Pacific-North America

## Mary Korendyke

## Introduction

Here is where I talk about why I'm doing what I'm doing. Atmospheric rivers: what are they? Why are they important for long-term forecasting?


## Data

ERA5 reanalysis and Metis199 and Metis639. ERA5 provides winds and specific humidity at x levels, so that vertically integerated moisture flux must be calculated using the same levels as exist in the EMCWF model used to create Metis forecasts. Metis forecasts come with column-integrated moisture flux already calculated. Include native grid resolutions in km. All data is interpolated to a Gaussian grid (128x64?), in km.

Link to ERA5 site
Link to Metis site

## Results/Code
- discuss how atmospheric rivers are measured (algorithm), link to AR identification from metisregimes project

### Climatology
- year-round atmospheric river climatology for ERA5
- extended winter AR climatology for k=5 clusters ERA5

[Monthly Climatology of ERA5 Atmospheric River Occurrences](https://github.com/mkorendyke/CLIM680/blob/master/hw2.ipynb)

### Winter-time Cluster Anomalies
- extended winter AR anoms for k=5 clusters ERA5
- significant differences in Metis anoms from ERA5 for extended winter AR k=5

### Atmospheric Rivers, the PNAI, and Nino3.4
- ERA5 PNA climate index
- Correlate ERA5 with Nino3.4
- Regress ERA5 with Nino3.4

[ERA5 November to March Atmospheric River Anomalies Composited on the Pacific North America Index] (https://github.com/mkorendyke/CLIM680/blob/master/hw3.ipynb)

## Summary
What have I learned? What do the results show? Is there anything particularly interesting?
