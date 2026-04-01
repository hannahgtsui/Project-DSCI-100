# DSCI 100 Project
# How Do Economic and Structural Influences Affect Cryptocurrency Adoption Across Countries?

## Group Members
- hannahgtsui
- kaheitang

## Introduction
As traditional financial and economic systems face increasing strain in many parts of the world, cryptocurrency has emerged as a potential alternative financial tool. This project examines whether broader forms of economic vulnerability — such as financial exclusion, income levels, macroeconomic instability, and structural differences including corruption — are associated with higher levels of cryptocurrency adoption across countries.

## Data Sources
- **World Bank** — Inflation, GDP per capita, Bank Access
- **Chainalysis** — Global Crypto Adoption Index (2024)
- **Kaggle** — Currency Depreciation
- **Transparency International** — Corruption Perceptions Index (CPI)

## Methods
This project uses supervised learning (linear regression) to predict cryptocurrency adoption scores from economic indicators.
- Part 1: Baseline Model — Linear regression with inflation, GDP, and bank access
- Part 2: Regional Differences in Crypto Adoption — Comparing adoption across geographic regions
- Part 3: Similarity among High-Adoption Countries — Comparing top 25% adopters with all countries
- Part 4: Extended Model — Adding currency depreciation and corruption index as predictors

## Key Findings
- Traditional economic indicators alone have limited explanatory power (R² = 0.063)
- Regional differences reveal significant variation, with North America and Central & Southern Asia leading
- High-adoption countries do not share a single distinct economic profile
- Adding currency depreciation and corruption index improves R² to approximately 0.19
- Cryptocurrency adoption is shaped by a combination of economic pressure and institutional context
