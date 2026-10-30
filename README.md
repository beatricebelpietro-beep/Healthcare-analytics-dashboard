# Healthcare-analytics-dashboard
Power BI dashboard analyzing healthcare expenditure, GDP per capita and life expectancy across 36 countries
# Healthcare Analytics Dashboard

[Dashboard Preview](dashboard_preview.png)

## Project Overview

This project analyzes the relationship between healthcare expenditure, national wealth, and life expectancy across 36 countries using data from the OECD and the World Bank.

The goal was to build an interactive Power BI dashboard that allows users to compare countries and identify patterns in healthcare spending, GDP per capita, and health outcomes.

## Data Sources

- OECD Health Statistics
- World Bank Open Data

The analysis uses country-level averages for the period 2015–2024.

## Tools Used

- **Excel** for data preparation and validation
- **Power Query** for cleaning and transforming the datasets
- **Power BI** for dashboard development and interactive visualization

## Data Preparation

The original datasets contained information on:

- Healthcare expenditure as a percentage of GDP
- Life expectancy
- GDP per capita in current US dollars

The datasets were cleaned, reshaped, and integrated into a consistent analytical structure. Country-level averages were then calculated for the 2015–2024 period.

The final workbook includes:

- `Raw_Data`
- `Country_Analysis`
- `PowerBI_Data`

## Dashboard Features

The Power BI dashboard includes:

- KPI cards for:
  - Number of countries
  - Average life expectancy
  - Average healthcare expenditure
  - Average GDP per capita
- Interactive country slicer
- Healthcare expenditure vs life expectancy scatter plot
- GDP per capita vs life expectancy scatter plot
- Bubble chart combining healthcare expenditure, life expectancy, and GDP per capita
- Top 10 countries by life expectancy
- Top 10 countries by healthcare expenditure
- Top 10 countries by GDP per capita
- Key insights panel

## Key Findings

- GDP per capita shows the strongest association with life expectancy among the indicators analyzed.
- Healthcare expenditure as a share of GDP shows a weaker relationship with life expectancy.
- Several countries achieve high life expectancy without being among the highest healthcare spenders.
- Broader socioeconomic and institutional factors appear important in explaining differences in health outcomes.

## Methodological Note

Healthcare expenditure is measured as a percentage of GDP, while GDP per capita is measured in current US dollars.

The analysis is descriptive and focuses on cross-country associations. The observed relationships should not be interpreted as causal effects.

## Repository Structure

```text
healthcare-analytics-dashboard/
│
├── README.md
├── dashboard_preview.png
└── healthcare_analytics_data.xlsx
```

## Skills Demonstrated

- Data cleaning and transformation
- Multi-source data integration
- Exploratory data analysis
- Cross-country benchmarking
- Power BI dashboard design
- Interactive data visualization
- Analytical interpretation
