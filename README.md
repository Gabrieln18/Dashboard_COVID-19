# COVID-19 Data Analysis Dashboard

### Description:

This project is dedicated to analyzing data on the evolution of COVID-19 in Brazil, the source of this data is available on the website: https://covid.saude.gov.br/.

## Dashboard Application

The dashboard used the Dash lib as the main library for its creation. To begin with, the application has components such as: 3D map (a chloropleth-type map was used), input calendar (to filter the dates in the data) and a line graph to track some data such as: Casos Acumulados, Casos Novos (new cases), Óbitos totais (total deaths), Óbitos por dia (deaths per day).

## How to use

The dashboard itself is fully interactive, it is possible to update the data by selecting the state on the indicated map. You can also filter the data using dates and select specific data using the dropdown.

## About the data used

As stated above, the data was imported through the website data portal: https://covid.saude.gov.br/.
The data has records since 2020-05-13.

## Libraries used

- Dash
- dash_core_components
- dash_bootstrap_components
- dash_html_components
- plotly
- pandas
- numpy
