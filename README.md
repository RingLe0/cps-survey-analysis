# Analysis of the Current Population Survey (CPS)

## Overview
This project analyzes data from the U.S. Current Population Survey (CPS)
to demonstrate applied statistical analysis using complex survey data.
The focus is on understanding how survey design and nonresponse affect
estimation and statistical inference.

## Data
- Source: Current Population Survey (CPS), public-use microdata
- Agencies: U.S. Census Bureau and Bureau of Labor Statistics
- Data type: Nationally representative household survey

## Research Questions
- What are the basic distributions of age and usual weekly hours worked?
- How does nonresponse relate to demographic characteristics?
- How do estimates and standard errors differ when survey design is ignored
  versus properly accounted for?

## Methods
- Descriptive statistical analysis
- Nonresponse analysis
- Survey-weighted estimation
- Variance estimation using Taylor series linearization
- Comparison with simple random sampling assumptions

## Key Findings
- CPS data exhibit nonrandom patterns of nonresponse
- Ignoring survey design can lead to misleading standard errors
- Design effects vary substantially across different variables

## Tools
- R
- survey package

## Files
- `Report_Analysis_of_the_Current_Population_Survey_(CPS).pdf`: Full project report

## Notes
This project emphasizes statistical reasoning and proper inference
when working with real-world survey data rather than predictive modeling.
