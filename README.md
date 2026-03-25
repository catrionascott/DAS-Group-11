# DAS-Group-11 Project 11: Obesity Prevalence

## Project Overview
This project analyses data from the Scottish Health Survey (2013–2016) to investigate patterns in obesity prevalence. The analysis focuses on whether obesity rates have changed over time and whether they differ across demographic and socio-economic groups.

## Research Questions
- Has the prevalence of obesity in Scotland changed between 2013 and 2016?
- Are there differences in obesity by age, sex, and employment status?

##  Data Description
The dataset (`DAProject11.csv`) contains the following variables:
- AgeGroup: Age category of individuals
- Sex: Male / Female
- Employment: Employment status
- Year: Survey year
- BMIgroup: Weight classification

##  Methods
- Exploratory Analysis (EA) using visualisations
- Logistic regression models:
  - Model 1: Obesity ~ Year
  - Model 2: Obesity ~ AgeGroup + Sex + Employment
