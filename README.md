# Project Title
**Exploratory Analysis of Diabetes Mortality Rates Across U.S. States and Demographic Groups (2015-2019)**

# Names and Affiliations
- **Julia Lin**, Emory University, QTM 302W  
- **Jessie Hao**, Emory University, QTM 302W 
- **Grace Song**, Emory University, QTM 302W 

# Project Overview

## Short Description of Project Objectives
This project aims to examine disparities in diabetes mortality rates from 2015 to 2019. We begin by identifying the racial group with the highest overall average mortality during this period. Focusing on this group, we then investigate whether geographic disparities exist across counties and states. If such disparities are present, we further identify the most vulnerable counties and states for targeted analysis.

## List of Methods Used
- **Data cleaning & preprocessing**
- **Summary statistics** of mortality trends
- **Visualizations**:
  - Boxplots by age group (IQR, medians, outliers)
  - Choropleth maps with `geom_polygon(color = "white")` & `scale_fill_viridis_c(option = "viridis")`
- **Geospatial mapping** using `sf`, `maps`, and `mapdata`

## List of Platforms/Languages
- **R**
- **Rstudio**
- **Packages:** `dplyr`, `ggplot2`, `stats`, `knitr`, `viridis`, `sf`, `maps`, `mapdata`

# Project Description

## Research Questions
1. Which racial group experiences the highest diabetes mortality?  
2. How do mortality patterns differ by age category?  
3. What county- or state-level hotspots emerge?  
4. Which demographic (age, race) and geographic (county, state) factors drive these disparities?

##  Models & Visualization Techniques
- **Transformation** of mortality rates to mortality per 10 million population  
- **Boxplots** to compare distributions across race and age groups
- **Choropleth maps** with Viridis color scales to highlight hotspots

## Challenges
- Data cleaning and filtering out relavant and non-repetitive observations
- Ensuring reproducible visualizations across collaborators
- Generalizability to post-pandemic situation 

## Future directions
- Incorporate post‑2020 data to assess the impact of COVID‑19  
- Add socioeconomic and healthcare access covariates  
- Build predictive models for identifying high‑risk areas
- Collaborate with local communities to develop culturally informed interventions

## Getting Started
```bash
# Clone the repository
git clone https://github.com/YourGitHubUsername/YourRepositoryName.git
cd YourRepositoryName
```
```r
# Install R dependencies
install.packages(c(
  "dplyr","ggplot2","sf","viridis",
  "knitr","maps","mapdata","stats"
))
```
Open `EDA_Final_Draft.Rmd` in your RStudio or `EDA_Final_Draft.html` in browser.  

## Directory Structure
```text
.
└── qtm302w-EDA/
    ├── data/
    │   ├── AIAN_data.csv
    │   ├── IHME_USA_DIABETES_COUNTY_RACE_ETHN_2000_2019_MX_2015_BOTH_Y2025M02D10.csv
    │   ├── IHME_USA_DIABETES_COUNTY_RACE_ETHN_2000_2019_MX_2016_BOTH_Y2025M02D10.csv
    │   ├── IHME_USA_DIABETES_COUNTY_RACE_ETHN_2000_2019_MX_2017_BOTH_Y2025M02D10.csv
    │   ├── IHME_USA_DIABETES_COUNTY_RACE_ETHN_2000_2019_MX_2018_BOTH_Y2025M02D10.csv
    │   └── IHME_USA_DIABETES_COUNTY_RACE_ETHN_2000_2019_MX_2019_BOTH_Y2025M02D10.csv
    ├── renv/
    │   ├── library/R-4.3/aarch64-apple-darwin20/renv
    │   ├── activate.R 
    │   └── settings.json
    ├── .gitattributes
    ├── EDA_Final_Draft.Rmd
    ├── EDA_Final_Draft.html
    ├── EDA_project.Rproj
    ├── README.md
    └── renv.lock
```
*(Generated using https://tree.nathanfriend.io)*

# Contact Info 
Grace Song, grace.song3@emory.edu
Jessie Hao, jessie.hao@emory.edu
Julia Lin, jingyi.lin@emory.edu

