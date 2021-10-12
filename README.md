# COVID_SIRV_model

This project (1) models the evolution of various COVID-19-related measurements over time and (2) computes a simulation of the SIRV (Susceptible, Infected, Removed, Vaccinated) model, an epidemiological model that computes the theoretical number of people infected with a contagious illness in a closed population over time.

We build the SIRV model simulations for several countries in the context of the COVID-19 pandemic. By making assumptions on parameters, we can estimate different scenarios under which the pandemic could develop.

### Files
- The [`project_overview.pdf`](./project_overview.pdf) file contains a more detailed explanation of the project
- The [`data`](./data) folder contains the data used in the analysis (last updated on 07/06/2021)

### Original data sources for each dataset

- `vaccinations`: https://www.kaggle.com/gpreda/covid-world-vaccination-progress
- `confirmed`, `deaths`, `recovered`: https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series from https://ourworldindata.org/coronavirus#coronavirus-country-profiles
- `population`: https://ourworldindata.org/search?q=population
