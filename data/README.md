# Data

This directory contains selected historical input datasets used in the original
Spring 2020 COVID-19 Data Bootcamp project.

The restored project preserves the original analytical time period rather than
updating the analysis with current COVID-19 data.

## Included raw data

### `country_population_2018.csv`

Historical country population data used to calculate COVID-19 cases relative
to population.

- Original project filename: `Country_population.csv`
- Source: World Bank
- Indicator: Total population
- Population year used in the original project: 2018

### `daily_new_covid_usa.csv`

Daily United States COVID-19 case data assembled for the original project from
CDC figures available during Spring 2020.

- Original project filename: `Daily_new_covid_usa.csv`
- Source referenced in the original notebook: U.S. Centers for Disease Control
  and Prevention (CDC)
- Historical project coverage: through approximately May 11, 2020

This file is retained as a historical project snapshot rather than reconstructed
from current CDC data.

### `gold_monthly.csv`

Monthly gold-price data used in the financial-market section of the project.

- Original project filename: `monthly_csv.csv`
- Recovered from the original `gold-prices` data package
- Data package source: Bundesbank
- Package distributed through DataHub
- Historical series used by the project extends through March 2020

## Other original project inputs

The original analysis also used state-level regression data and historical
financial-market CSV files. Those recovered files are being preserved separately
from this repository while their provenance and redistribution status are
documented.

The source-only historical notebook therefore preserves the original code and
filenames, while the restored notebook uses the curated project data structure
documented here.