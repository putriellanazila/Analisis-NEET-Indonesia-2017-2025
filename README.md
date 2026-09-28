# Analisis NEET Indonesia 2017–2025

## Overview

This project analyzes factors associated with the **Not in Employment, Education, or Training (NEET)** rate across 34 provinces in Indonesia during the 2017–2025 period.

The analysis uses **panel data regression with interaction effects** to examine the moderating roles of ICT skills and income inequality. **Clustered-robust standard errors at the provincial level** are applied to obtain robust standard error estimates that account for within-province correlation.

## Objectives

- Analyze factors associated with the NEET rate in Indonesia.
- Examine the moderating role of ICT skills.
- Examine the moderating role of income inequality.

## Tools

- Python
- Pandas
- Statsmodels
- Linearmodels
- Excel

## Dataset

The dataset consists of provincial-level secondary data sourced from the **Statistics Indonesia (BPS)**.

- **Observation period:** 2017–2025
- **Unit of analysis:** 34 provinces in Indonesia

## Methodology

The analysis consists of the following stages:

1. Data preprocessing
2. Exploratory Data Analysis (EDA)
3. Variable transformation
4. Multicollinearity assessment
5. Panel data model selection
6. Classical assumption tests
7. Interaction effect analysis
8. Clustered-robust standard errors
9. Model interpretation

## Variables

### Dependent Variable

- NEET

### Independent Variables

- Human Development Index (HDI)
- Unemployment Rate
- Labor Force Participation Rate
- Informal Employment
- Mean Years of Schooling
- Poverty Rate
- Population Density

### Moderating Variables

- ICT Skills
- Income Inequality (Gini Ratio)

## Repository Structure

```text
Analisis-NEET-Indonesia-2017-2025/
│
├── README.md
├── notebook/
├── figures/
├── output/
└── data/
