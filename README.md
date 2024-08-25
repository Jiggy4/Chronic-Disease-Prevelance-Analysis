# Project Architecture for Chronic Disease Prevalence Analysis

## Overview
This project focuses on analyzing the prevalence of chronic diseases among seniors aged 65+ across the nine U.S. Census districts. The goal is to identify the prevalence rates of COPD, diabetes, and osteoporosis within these regions, and provide insights that could guide public health planning and resource allocation for a health insurance company's potential market expansion.

## Data Description
### Dataset 1: Geographic Variation Public Use File
-  State-level population data for the year 2020
- **Features:** `STATE`, `AGE_LVL`, `Bene_Geo_Cd`, `Bene_Age_Lvl`, `Bene_Cond`, `Prvlnc`
- **Target Variable:** Prevalence of COPD, diabetes, and osteoporosis

### Dataset 2: Chronic Disease Data
- **Dataset Size:** State-level chronic disease prevalence data for the year 2020
- **Features:** `STATE`, `Bene_Age_Lvl`, `Bene_Cond`, `Prvlnc`
- **Target Variable:** Population-weighted average prevalence of chronic diseases across census districts

## Methodology
### Data Processing
 **Population-Weighted Average Calculation**: The prevalence of each chronic condition for each Census district was calculated by taking a population-weighted average of the prevalence rates across the states within that district.


### Tools Used
- **Excel**: For data cleaning and automating data processing and calculations.

- **PowerPoint**: For presenting the findings.


## Analysis & Findings
### COPD
- **Highest Prevalence**: District 6 (East South Central) at 13.8%
- **Lowest Prevalence**: Districts 8 and 9 (Mountain and Pacific) at 9-10%

### Diabetes
- **Highest Prevalence**: Districts 2 and 6 (Middle Atlantic and East South Central) at 29-30%
- **Lowest Prevalence**: Districts 8 and 9 (Mountain and Pacific) at 22-25%

### Osteoporosis
- **Highest Prevalence**: District 2 (Middle Atlantic) at 8.02%
- **Lowest Prevalence**: District 6 (East South Central) at 6.6%

### Key Findings
- **Disease Prevalence Trends**: Diabetes is the most prevalent chronic disease among seniors, followed by COPD and osteoporosis.
- **Regional Disparities**: Southern districts exhibit higher COPD and diabetes prevalence, potentially due to risk factors like smoking, obesity, diet, or genetic conditions. The Mountain and Pacific districts have comparatively lower prevalence rates across all three conditions.
- **Public Health Implications**: Understanding these regional differences is crucial for guiding public health strategies and resource allocation.

## Practical Applications
- **Healthcare Strategy Development**: The analysis provides insights that could help health insurance companies tailor benefit plans according to regional disease prevalence, ensuring that resources are allocated efficiently and effectively.

## Limitations
- The analysis is limited to data from 2020 and only considers seniors aged 65+.
- Population-weighted averages may not fully capture the nuances of state-specific factors influencing disease prevalence.

## Future Work
- **Expand Analysis**: Incorporate more recent data and consider additional chronic conditions.
- **Broaden Scope**: Extend the study to younger populations and explore the impact of socio-economic factors on disease prevalence.

