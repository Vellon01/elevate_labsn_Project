
# Global CO₂ Emissions by Source and Country

## Overview

This project presents an interactive Tableau dashboard that visualizes global carbon dioxide (CO₂) emissions by country and by emission source—coal, oil, gas, and industry. The goal is to help stakeholders understand emissions distribution and support data-driven climate policy.

## Dataset

**Source**: Processed from publicly available global emissions data  
**File Used**: `cleaned_emissions_data.csv`  
**Key Fields**:
- `country`
- `year`
- `co2`, `co2_per_capita`, `co2_per_gdp`
- `coal_co2`, `oil_co2`, `gas_co2`, `other_industry_co2`
- `population`, `gdp`

## Dashboard Features

- Map View: Total CO₂ emissions by country
- Stacked Bar Chart: Emissions breakdown by source (coal, oil, gas, industry)
- Line Chart: CO₂ emissions trends over time
- Bubble Chart: Emissions per capita vs GDP
- Filters:
  - Year selector
  - Country selector
  - Emission source (optional)

## Tools Used

- Tableau: For interactive dashboard and data visualizations  
- Python: For cleaning and preprocessing the dataset

## How to Use

1. Open Tableau and connect to `cleaned_emissions_data.csv`
2. Use provided calculated fields or pivot for sector-wise stacking
3. Build charts as outlined in the project guide
4. Assemble them into an interactive dashboard
5. Export or publish to Tableau Public or as PDF

## Objective

To provide a visual, accessible, and data-driven understanding of:
- Which countries are the top CO₂ emitters
- How emissions vary by energy source
- Trends in emissions growth or decline
- Per capita and per GDP emission comparisons
