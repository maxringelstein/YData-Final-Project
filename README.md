# YData Final Project: An Analysis of Gun Violence Data in the US (2014–2017)

## Overview
This project analyzes trends in gun violence across the United States from 2014 to 2017 using a dataset of over 200,000 recorded incidents sourced from the [Gun Violence Archive](https://www.gunviolencearchive.org/) via [this GitHub repository](https://github.com/jamesqo/gun-violence-data).

This was completed as the final project for YData (S&DS 1230) at Yale University and received an A.

## Key Questions Explored
- Where are shootings most concentrated geographically?
- How have incidents changed over time?
- What is the age profile of gun violence offenders?

## Key Findings
- Gun violence is heavily concentrated in large metropolitan areas, particularly along the East Coast and Midwest
- Chicago alone accounted for nearly 62% of all shootings in Illinois, and had 2.7x more shootings than the next highest city (Baltimore)
- Incidents peak in summer months (June–August) and showed a statistically significant upward trend from 2014–2017
- The most common age of a gun violence offender was 19, with a mean of ~29 and a median of 26

## Visualizations
1. **Geographic Distribution** — Map of all shootings across the contiguous US, with the 20 highest-incident cities labeled
2. **Shootings by State & City** — Ranked bar charts for all 50 states and top 50 cities
3. **Temporal Trends** — Monthly incident counts with regression line and 95% confidence interval, plus seasonal patterns by year
4. **Age Distribution** — Histogram and KDE of offender ages with mean, median, and mode marked

## Tools & Libraries
`Python` · `Pandas` · `GeoPandas` · `Seaborn` · `Matplotlib` · `NumPy`

## Data Source
[Gun Violence Archive](https://www.gunviolencearchive.org/) via [jamesqo/gun-violence-data](https://github.com/jamesqo/gun-violence-data) — 222,215 incidents recorded between January 2013 and March 2018.

*Note: Data from 2013 and early 2018 were excluded from analysis due to incomplete records.*
