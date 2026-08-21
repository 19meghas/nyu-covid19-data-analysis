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




## Johns Hopkins COVID-19 historical snapshot

The restored notebook uses locally preserved historical snapshots from the
Johns Hopkins University CSSE COVID-19 Data Repository rather than the
repository's current files.

This avoids silently incorporating revisions or observations added after the
original Spring 2020 project period.

### Time-series datasets

The following five files were recovered from the JHU `master` branch:

- `time_series_covid19_confirmed_global.csv`
- `time_series_covid19_deaths_global.csv`
- `time_series_covid19_recovered_global.csv`
- `time_series_covid19_confirmed_US.csv`
- `time_series_covid19_deaths_US.csv`

Git commit:

`c02666a966cfe00eca2cb5b39ad520f34c6dd07e`

At this repository state, all five time-series datasets end on May 13, 2020,
matching the historical analysis window of the original project.

### Country-level snapshot

`cases_country.csv` was recovered separately from the JHU `web-data` branch.

Git commit:

`690d118a3b4f301f0ed7803fcc7a80bea529cfb8`

The first country record reports:

`Last_Update = 2020-05-13 23:32:26`

which matches the country-level data timestamp preserved in the original
Spring 2020 notebook output.




## New York City COVID-19 historical snapshot

The restored notebook uses locally preserved historical data from the New York
City Department of Health and Mental Hygiene COVID-19 repository rather than
the repository's current files.

The original project referenced these files directly from the live NYC Health
GitHub repository:

- `case-hosp-death.csv`
- `by-age.csv`
- `by-sex.csv`

For reproducibility, the restored project pins all three files to the same
historical repository state:

`6b501e5e4fbe09d49d454e00e18205dd6fec9bff`

At this commit, `case-hosp-death.csv` ends with:

`5/11/20,26,0,3`

which matches the final daily record preserved in the original Spring 2020
notebook.

These files are retained as historical snapshots because the NYC Health
COVID-19 repository was subsequently reorganized and its datasets changed over
time.