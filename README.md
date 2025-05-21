# Titanic Survival Analysis

## Overview
This repository contains a statistical analysis of the relationship between passenger class and survival during the Titanic disaster. Using chi-square tests for independence, this project examines whether a passenger's class (1st, 2nd, 3rd, or Crew) had a significant impact on their chances of survival when the ship sank in 1912.

## Project Description
The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. This statistical analysis treats the Titanic disaster as a random observation from all possible outcomes, allowing us to use hypothesis testing to investigate factors that influenced survival.

The primary question investigated is: **Was a passenger's survival independent of their class aboard the Titanic?**

## Files in this Repository
- `STAT311-HW6-Writeup.Rmd` - R Markdown document containing the complete analysis
- `STAT311-HW6-Writeup.pdf` - Compiled PDF output of the analysis
- `STAT311-HW6.R` - R script containing the code for statistical hypothesis tests

## Analysis Methods
This project implements:
- Contingency table analysis
- Chi-square test for independence
- Interpretation of expected values
- P-value analysis and hypothesis testing
- Consideration of confounding variables (age, sex)

## Key Findings
The analysis reveals a statistically significant relationship between passenger class and survival rates during the Titanic disaster. The data strongly suggests that a passenger's class influenced their probability of survival, with higher classes generally showing better survival rates.

Additionally, the project explores how the demographic composition of each class (the distribution of men, women, and children) may have confounded this relationship, suggesting directions for more complex multivariate analysis.

## Technologies Used
- R Statistical Programming Language
- R Markdown for reproducible research documentation
- The following R packages:
  - `knitr` for document compilation
  - Base R statistical functions

## How to Run
To reproduce this analysis:

1. Clone this repository
   ```
   git clone https://github.com/username/titanic-survival-analysis.git
   cd titanic-survival-analysis
   ```

2. Open the R Markdown document in RStudio
   ```
   STAT311-HW6-Writeup.Rmd
   ```

3. Install any required packages
   ```r
   install.packages(c("knitr", "rmarkdown"))
   ```

4. Run all chunks or knit the document to reproduce the analysis

## Prerequisites
- R (version 4.0.0 or higher recommended)
- RStudio (for easiest reproduction of R Markdown documents)

## Academic Context
This project was completed as part of STAT311 coursework, focusing on statistical hypothesis testing and categorical data analysis.

## Data Source
The data is sourced from the built-in `Titanic` dataset in R, which contains information on the fate of passengers aboard the Titanic, summarized according to economic status (class), sex, age, and survival.

## License
This project is submitted as academic coursework and is provided for educational purposes.

---

*Note: This analysis acknowledges the tragic nature of the historical event it examines and approaches the data from a purely academic perspective to better understand statistical patterns in survival outcomes.*
