# Education and Attitudes Toward Immigration in the Netherlands

## View the project

[View the rendered analysis] [https://jinfang-zhang.github.io/Immigration-Attitude-toward-Immigration/](https://jinfang-zhang.github.io/Immigration-Attitude-toward-Immigration/)

## About

This project is based on a course assignment from my MSc in Social Scientific Data Analysis at Lund University.

I used data from Round 10 of the European Social Survey (ESS) to examine the relationship between education and attitudes toward immigration in the Netherlands. I later revisited the assignment, cleaned up the code, simplified the analysis, and improved the visualizations for this portfolio version.

**Research question:**  
To what extent is education associated with attitudes toward immigration in the Netherlands?

## Analysis

The project includes:

- data cleaning and recoding
- construction and reliability testing of an immigration attitude index
- exploratory visualization
- multiple linear regression
- HC3 robust standard errors
- VIF checks
- coefficient visualization

All regression models use the same complete-case sample to make model comparisons more consistent.

## Key findings

Education is positively associated with attitudes toward immigration across all model specifications.

The association remains statistically significant after accounting for sociodemographic, economic, and attitudinal characteristics. Social trust, cultural values, and country of birth are also significant predictors in the extended model.

Because the data are cross-sectional and observational, the results should be interpreted as associations rather than causal effects.

## Files

- `Project.Rmd` — R Markdown source file
- `index.html` — rendered analysis

## Tools

R · tidyverse · ggplot2 · linear regression · robust standard errors
