# Project Title
**Diabetes Mortality Rates Across U.S. States and Demographic Groups (2015-2019)**

# Names and Affiliations
Julia Lin, Jessie Hao, Grace Song  
Emory University, QTM 302W

# Project Overview

## Short Description of Project Objectives
This project explores disparities in diabetes mortality rates across U.S. states from 2015 to 2019, with particular attention to differences among age groups and geographical locations. Our goal is to identify trends and factors that contribute to the risk of diabetes mortality observed in certain racial groups.

## List of Methods Used
- Data Cleaning and Preprocessing
- Data Visualization
- Geographic Mapping
- Statistical Testing

## List of Platforms/Languages
- R
- RStudio
- Libraries: `tidyverse`, `plotly`, `viridis`, `dplyr`, `ggplot2`, `maps`, `mapdata`, `stats`, `knitr`, `viridis`, `sf`

# Project Description

## Research Questions
- Which racial groups have the highest diabetes mortality rates in the U.S.?
- How does age distribution contribute to differences in mortality among racial groups?
- How does mortality vary geographically across states and counties?

## Specific Models and Visualization Techniques
- **Mapping:** Dynamic and static choropleth maps showing mortality by state and racial group.
- **Trendlines:** Time-series plots tracking mortality changes across years.

## Challenges Faced
- Balancing between granularity (county-level) and interpretability (state-level) due to data sparsity.
- Harmonizing naming conventions across geographic datasets (e.g., lowercase states).

## Potential Next Steps (Future Directions)
- Incorporate socioeconomic variables (e.g., income, education) to better explain disparities.
- Expand on the time period to allow observations based on more recent data.
- Expand analyses to include comorbidities like obesity or cardiovascular disease.
- Apply predictive modeling to forecast future trends in diabetes mortality.

# Instructions for Getting Started
1. Clone the repository.
2. Open the R Project file (`.Rproj`) or open scripts directly in RStudio.
3. Install necessary R packages:
   ```r
   install.packages(c("tidyverse", "plotly", "viridis", "maps", "mapdata"))
   
/ (root)
|-- README.md
|-- EDA_Final_Draft.html
|-- data/
|    |-- state_comb_data.csv
|    |-- state_AIAN_data.csv
|    |-- age_all_data.csv
|-- scripts/
|    |-- data_cleaning.R
|    |-- exploratory_analysis.R
|    |-- final_visualizations.R
|-- figures/
|    |-- state_maps/
|    |-- race_age_piecharts/
|    |-- trendlines/

# Contact Info 
Grace Song, grace.song3@emory.edu
Jessie Hao, jessie.hao@emory.edu
Julia Lin, jingyi.lin@emory.edu

