# Project 01 — Exploratory Data Analysis: Nigerian Housing Market

## Overview
An end-to-end EDA project on a Nigerian housing dataset spanning five major cities —
Lagos, Abuja, Port Harcourt, Ibadan, and Kano. The project covers data cleaning,
descriptive statistics, feature engineering, and visualisation, with a written
insight narrative for each chart.

## Skills Demonstrated
- Data loading and inspection with Pandas
- Identifying and fixing real-world data quality issues
- Descriptive statistics and aggregation
- Feature engineering (price per square metre)
- Data visualisation with Matplotlib
- Translating visual findings into written analysis

## Project Structure
project-01/
├── Project01_Nigerian_Housing_EDA.ipynb   # Main notebook
├── nigeria_housing.csv                    # Raw dataset (120 properties)
├── nigeria_housing_clean.csv              # Cleaned dataset (output)
└── README.md

## Dataset
A curated dataset of 120 residential properties across Lagos, Abuja, Port Harcourt,
Ibadan, and Kano. Columns include property type, size, number of bedrooms, condition,
year built, and listed price in ₦ million. The dataset contains deliberate data
quality issues introduced for cleaning practice.

## Key Findings
- Abuja and Lagos consistently command the highest property prices, with Abuja
  edging Lagos on a price-per-sqm basis despite lower absolute median prices.
- Property condition has a steep impact on price — a "Needs Renovation" property
  sells for significantly less than a comparable "New" listing.
- Bedrooms and size are the strongest numeric predictors of price, though 
  significant variance at every bedroom count suggests location drives much
  of the premium.

## Tools
Python · Pandas · NumPy · Matplotlib · Jupyter Notebook

## Note
This exercise was designed with the assistance of Claude (Anthropic) as part of a
structured ML learning roadmap. If you'd like to work through it yourself, feel free
to download the blank notebook.
