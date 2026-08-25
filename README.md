# Early COVID-19 Data Analysis

A historical data science project exploring the early spread of COVID-19 across global, United States, and New York City data, alongside exploratory statistical and financial-market analysis.

This project was originally completed as a three-person final project for the **NYU Stern Data Bootcamp in Spring 2020**, during the opening months of the COVID-19 pandemic in New York City.

> **Restoration status:** This repository contains a restored and polished version of the original Spring 2020 project. The restoration improves reproducibility, organization, documentation, code clarity, and analytical presentation while preserving the historical scope and collaborative nature of the original work.

## Project background

The project was developed while COVID-19 was still rapidly unfolding and while public datasets, reporting practices, and understanding of the pandemic were changing almost daily.

### Why this project

The idea for this project emerged during the opening weeks of my final semester at NYU in Spring 2020. During the weekend of February 7, 2020, I was participating in the Cornell AI Health Hackathon while news of the novel coronavirus outbreak in China was beginning to attract increasing international attention. COVID-19 was still an emerging global story, and New York City had not yet experienced the outbreak that would soon transform daily life there. Against that backdrop, I became interested in using the rapidly evolving public data as the basis for our Data Bootcamp final project.

The context changed remarkably quickly. Within weeks, New York City began reporting a rapidly growing number of cases, and NYU suspended in-person classes in March. What initially appeared to be a temporary move to remote instruction ultimately continued through the remainder of the semester.

As New York became one of the earliest and hardest-hit US population centers, the subject of the project became part of the environment in which we were completing it. While living through the first major New York outbreak, I continued working with my teammates on analyses spanning global COVID-19 patterns, the United States, and New York City, using data that were still being released and revised in real time through May 2020.

The project brought together several analytical perspectives to explore questions such as:

* How were confirmed COVID-19 cases distributed globally?
* How did reported case counts evolve across countries over time?
* How did case volumes compare with country population size?
* Which parts of the United States were reporting the highest case volumes?
* How were cases, hospitalizations, and deaths evolving in New York City?
* Which state-level characteristics were associated with reported COVID-19 testing volumes?
* How were selected financial markets and companies behaving during the early pandemic period?

The final notebook combined descriptive analysis, interactive visualization, geographic mapping, animation, regression, and financial-market exploration.

## Collaboration and my role

The project was developed collaboratively by a three-person team.

I conceived the project and shaped its overall analytical direction, including the core questions and structure of the analysis. My work focused on the global COVID-19, United States, and New York City sections, alongside coordinating the division of analytical work across the team.

One teammate developed the animated bar-chart race after I proposed it as an additional visualization for the project. Alexandre worked on the state-level regression and financial-market sections.

As the individual workstreams came together, I also integrated the different sections into the combined notebook and worked on organizing the final analytical flow and presentation.

A more detailed contribution record is available in [`CONTRIBUTIONS.md`](CONTRIBUTIONS.md).

## Analytical scope

### 1. Global COVID-19 analysis

The global section explored:

* Worldwide confirmed cases, deaths, and recoveries
* Country-level comparisons
* Geographic distribution of reported cases
* Population-adjusted comparisons
* Interactive country visualizations
* An animated bar-chart race showing how country rankings changed over time

### 2. United States and New York City analysis

The project examined:

* COVID-19 case distribution across the United States
* Geographic patterns across US states
* Daily US case trends
* New York City case trends
* Hospitalizations
* Deaths
* Age-based patterns
* Sex-based patterns

### 3. State-level regression analysis

The project explored relationships between reported COVID-19 testing volumes and selected state-level characteristics.

Variables considered included measures related to:

* Physician counts
* Population
* Income
* Healthcare spending
* Pollution

The original analysis included both simple and multiple regression models.

### 4. Financial-market analysis

The project also explored selected financial indicators during the early pandemic period, including:

* Dow Jones Industrial Average
* S&P 500
* NASDAQ Composite
* Zoom
* Delta Air Lines
* Expedia
* Gold prices

These analyses were exploratory and descriptive rather than causal.

## Historical data period

Most of the COVID-19 analysis reflects data available through approximately **May 12–13, 2020**, while several financial datasets extend through **April 24, 2020**.

The recovered project archive also contains later copies in which some live-data cells were rerun after the course ended. The restored version therefore uses the Spring 2020 project period as its historical reference point rather than silently incorporating later observations.

## Original tools and libraries

The original project was developed in Python using Jupyter Notebook and libraries including:

* Pandas
* NumPy
* Matplotlib
* Plotly
* Folium
* Statsmodels
* Matplotlib animation tools

The analysis combined data from multiple public and historical sources, including COVID-19 time-series data, population data, state-level indicators, financial-market data, and gold-price data.

Source provenance and historical-data decisions are documented in the restored notebook and repository materials where the original sources could be established confidently.

## Repository structure

```text
nyu-covid19-data-analysis/
├── README.md
├── CONTRIBUTIONS.md
├── .gitignore
├── assets/
├── data/
│   ├── raw/
│   └── processed/
├── docs/
└── notebooks/
```

Repository contents:

* `notebooks/` contains the restored analytical notebook and selected historical artifacts.
* `data/raw/` contains historical source files required for reproducibility where appropriate.
* `data/processed/` contains cleaned or transformed datasets created during the restoration.
* `assets/` contains selected charts, images, and animation outputs.
* `docs/` contains methodology, data-source, and restoration documentation.

## Restoration approach

The goal of this work is not to redesign the original project as though it had been created with later knowledge or more advanced experience.

Instead, the restoration preserves the original analytical intent while improving the way the project is organized, executed, and communicated.

Restoration work completed includes:

* Preserving the original Spring 2020 project as a historical artifact
* Identifying and documenting the historical data inputs used in the analysis
* Establishing reproducible local or historically pinned data sources
* Removing broken file paths and stale notebook state
* Consolidating repeated imports and code
* Replacing fragile position-based data handling with explicit and validated logic
* Improving visualization consistency and readability
* Clarifying statistical interpretation where appropriate
* Documenting assumptions, limitations, and data provenance
* Distinguishing original 2020 work from later restoration changes

## Collaboration and attribution

Contributors are named publicly where permission has been confirmed. Other collaborators remain referred to as teammates until their preferred public attribution is confirmed.

The animated bar-chart-race implementation was adapted from examples by **Pratap Vardhan** and **John Burn-Murdoch**. Their work was credited in the historical notebook and remains credited in the restored version.

See [`CONTRIBUTIONS.md`](CONTRIBUTIONS.md) for additional detail.

## Historical context and limitations

This project should be interpreted as an analysis conducted during the first months of the COVID-19 pandemic using incomplete and rapidly evolving data.

At the time, testing availability, reporting practices, case definitions, and data quality varied substantially across locations. Many relationships explored in the project are therefore descriptive or associative and should not be interpreted as causal conclusions.

The restored repository retains that historical context rather than evaluating the original work using information that only became available later.
