# Sleep_medication_analysis

## UMich LHS 610 - Final Project
This analysis (and corresponding report) was developed as the final project for the University of Michigan's LHS 610 (Exploratory Data Analysis for Health) course. The goal of this assignment was to demonstrate an ability to formulate a health-related question (ie identifying the population, intervention, comparison group, and outcome), find the necessary data, and apply basic exploratory data analysis techniques to investigate the hypothesis. We were asked to investigate the relationship between the exposure variable and the outcome variable through an appropriate statistical test and accompanying visualization, as well as the relationship between the exposure and the outcome stratified by two confounders. 

I chose to investigate the relationship between sleep medication and sleep quality in adults. We were not to asked to do causal analysis, so this paper only assesses the association between the variables. The data was sourced from the 2022 National Health Interview Survey. More information on methods and outcomes of my analysis can be found in the report. 

## Set Up
### Dependencies
The course was taught in R, so the analysis was written in an R Markdown file. I recommend running the file in RStudio, but any IDE that supports R and the knitr package will do. 

- `tidyverse`
- `ggplot2`
- `scales`
