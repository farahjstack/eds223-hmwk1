# Environmental Justice Mapping in Denver County, Colorado

## About
This repository contains *Assignment 1* for *EDS 223: Geospatial Analysis and Remote Sending*, part of the Master of Environmental Data Science (MEDS) program at the Bren School of Environmental Science & Management, University of California, Santa Barbara.

This assignments uses the U.S. Environmental Protection Agency's (EPA) 2023 EJScreen dataset to explore environmental injustices in Denver County, Colorado. Two maps illustrate the geographic distribution of fine particulate matter (PM2.5) concentrations and unemployment rates at the census block group-level.

The goal of this analysis is to explore potential patterns of environmental inequities and examine how socioeconomic conditions may intersect with air pollution exposure.

## Repository Contents
- *Quarto document (.qmd)*: R code, maps, and written analysis.
- *git.ignore*: Excludes locally stores files from Git version control.
- *README.md*: Project overview, data information, and references.

## Data
*Source*: U.S. Environmental Protection Agency (EPA), EJScreen 2023.

The analysis uses census block group-level EJScreen data filtered to Denver County, Colorado. The dataset includes environmental and demographic indicators used to evaluate environmental justice concerns.

The dataset files are used for the analysis and supporting documentation:
- *EJSCREEN_2023_BG_StatePct_with_AS_CNMI_GU_VI.gdb* - Geodatabase containing environmental and demographic data

- *ejscreen-tech-doc-version-2-2.pdf* - EJScreen technical documentation.

- *EJSCREEN_2023_BG_Columns.xlsx* - Dataset column descriptions.

# Reproducing the Analysis
1. Clone of download this GitHub repository
2. Download the 2023 EJScreen dataset and place the geodatabse in the `data/ejscreen`/directory.
3. Open the Quarto (.qmd) document in an R-compatible environment.
4. Install the required R packages.
5. Run the code and render the Quarto document to generate the maps and accompanying analysis.

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
