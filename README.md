# Education and Attitudes Toward Immigration in the Netherlands

## Overview

This project examines the relationship between education and attitudes toward
immigration in the Netherlands using data from Round 10 of the European Social
Survey (ESS).

The analysis focuses on whether individuals with more years of education tend
to hold more positive attitudes toward immigration, while accounting for
sociodemographic, economic, and attitudinal characteristics.

The project demonstrates an end-to-end statistical analysis workflow in R,
including data cleaning, scale construction, exploratory analysis, multiple
linear regression, robust inference, model diagnostics, and visualization.

## Research Question

**To what extent is education associated with attitudes toward immigration in
the Netherlands?**

## Data

The analysis uses data from Round 10 of the European Social Survey (ESS) and focuses on
respondents from the Netherlands. (The raw dataset is not included in this repository.)

Attitudes toward immigration are measured using a composite index based on
three survey items assessing perceptions of immigration's:

- economic impact
- cultural impact
- overall impact on the country

The three items showed acceptable internal consistency
(Cronbach's α = 0.78).

## Methods

The analysis includes:

- Data cleaning and recoding
- Composite index construction
- Cronbach's alpha reliability analysis
- Exploratory data analysis
- Bivariate linear regression
- Multiple linear regression with sociodemographic controls
- Extended regression models including economic and attitudinal predictors
- HC3 heteroskedasticity-robust standard errors
- Multicollinearity and influence diagnostics
- Regression and coefficient visualization

## Key Findings

- Higher levels of education were consistently associated with more positive
  attitudes toward immigration across all model specifications.

- In the bivariate model, each additional year of education was associated
  with approximately a 0.10-point increase in the immigration attitude index.

- After adjusting for sociodemographic, economic, and attitudinal factors, the
  association remained statistically significant.

- Social trust and cultural values were also positively associated with
  immigration attitudes in the extended model.

- Respondents born outside the Netherlands reported more positive attitudes
  toward immigration, controlling for other variables.

- Results remained substantively unchanged when HC3 robust standard errors
  were used.

- VIF values were below 1.5, indicating no meaningful multicollinearity among
  predictors.

## Tools

**R · tidyverse · ggplot2 · psych · modelsummary · broom · sandwich · lmtest**

## Limitations

The analysis uses cross-sectional observational survey data. Results therefore
represent statistical associations and should not be interpreted as causal
effects.

## Repository Contents

- `education_immigration_attitudes.Rmd` – complete R analysis
- `education_immigration_attitudes.html` – rendered analysis
- `figures/` – key visualizations
