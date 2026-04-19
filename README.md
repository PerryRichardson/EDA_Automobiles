# Capstone Project - Exploratory Data Analysis: Automobile Dataset

This repository contains my completed Capstone Project for the
HyperionDev Data Science Bootcamp.

## Project Overview

An exploratory data analysis (EDA) was performed on the automobile
dataset, covering 205 cars across 26 variables. The analysis
investigates pricing, fuel efficiency, engine size, and manufacturer
representation.

## Repository Structure

EDA_Automobiles/
├── automobiles_eda.ipynb                 # Main EDA notebook
├── automobile.txt                        # Raw dataset
├── automobiles_raw.csv                   # Copy of raw data before cleaning
├── EDA Report - Automobile Dataset.pdf   # EDA report
└── Figures/                              # Charts generated during analysis
    ├── most_expensive_cars_mpg.png
    ├── avg_mpg_by_manufacturer.png
    ├── largest_engines.png
    └── models_per_manufacturer.png

## Analysis Questions

1. Which automobiles are in the hatchback category?
2. Which are the 5 most expensive cars?
3. Which manufacturer builds the most fuel efficient vehicles?
4. Which vehicles have the largest engine capacity?
5. Which vehicle manufacturer has the most car models in the dataset?

## Libraries Used

- pandas
- numpy
- matplotlib
- seaborn

## How to Run

1. Clone the repository
2. Install dependencies: pip install pandas numpy matplotlib seaborn
3. Open automobiles_eda.ipynb in Jupyter or VS Code and run all cells