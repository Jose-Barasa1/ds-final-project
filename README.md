# Aviation Risk Analysis (1962–2023)

## Overview
This project analyzes aviation accident data (1962–2023) to identify low-risk aircraft, detect high-risk operators and regions, and provide data-driven recommendations for safer fleet procurement and operations. Analysis and cleaning were performed in Python (Pandas). Visualizations and an interactive dashboard are available via Tableau (link provided below).

## Problem Statement
Accidents in aviation are still concentrated among certain aircraft types, operators and regions. The company needs a simple, data-driven way to identify the safest aircraft and understand the main drivers of accident risk to make procurement and safety decisions.

## Solution 
- Clean and standardize NTSB accident records.  
- Analyze trends over time, fatalities, operators, countries and aircraft types.  
- Build visualizations and an interactive Tableau dashboard.  
- Produce clear recommendations for procurement, regulation and training.

---

## Dataset
- Source: National Transportation Safety Board (NTSB) (downloaded CSV)  
- Filename used in the analysis: `aviation-accident-data-2023-05-16.csv`  
- Cleaned dataset exported: `cleaned_aviation_data.csv`  
- Coverage: 1962–2023, ~23,967 records, ~9 columns (Date, Type, Registration, Operator, Fatalities, Location, Country, Category, Year)

---

## Repository (how to access the project)
1. Clone the repository (replace placeholder with actual repo URL):
```bash
git clone  git@github.com:Jose-Barasa1/ds-final-project.git 
cd ds-final-project
