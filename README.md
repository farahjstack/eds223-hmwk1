# Environmental Justice Mapping in Denver County, Colorado

## About
This repository contains *Assignment 1* for *EDS 223: Geospatial Analysis and Remote Sending*, part of the Master of Environmental Data Science (MEDS) program at the Bren School of Environmental Science & Management, University of California, Santa Barbara.

This assignments uses the U.S. Environmental Protection Agency's (EPA) 2023 EJScreen dataset to explore environmental injustices in Denver County, Colorado. Two maps illustrate the geographic distribution of fine particulate matter (PM2.5) concentrations and unemployment rates at the census block group-level.

The goal of this analysis is to explore potential patterns of environmental inequities and examine how socioeconomic conditions may intersect with air pollution exposure.

## Repository Contents
- *Quarto document (.qmd)*: R code, maps, and written analysis.
- *README.md*: Project overview, data information, and references.

## Data
*Source*: U.S. Environmental Protection Agency (EPA), EJScreen 2023.

The analysis uses census block group-level EJScreen data filtered to Denver County, Colorado.

The dataset includes environmental and demographic indicators used to evaluate potential environmental injustices.

# Methods
Spatial data were processed and visualized in R using the following packages:
- `tidyverse`
- `sf`
- `here`
- `stars`
- `tmap`
- `RColorBrewer`

# Author
Farah Stack

# References
U.S. Environmental Protection Agency. (2023). _EJScreen: Environmental Justice Screening and Mapping Tool._ https://www.epa.gov.ejscreen

UCSB Master of Environmental Data Science. _EDS 223: Geospatial Analysis and Remote Sensing_. https://eds-223-geospatial.github.io.

# Acknowledgements
Special thanks to Professor Annie Adams and Teaching Assistant Mary Salami for their instruction and guidance throughout EDS 223. Additional appreciation goes to the *UCSB Meds Class of 2027 cohort* for their collaboration, shared learning, and support.
