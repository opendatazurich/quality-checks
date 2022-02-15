quality-checks
==============

Python environment (Jupyter Notebook) to run various checks on tabular data, including:

* Plausibility check (e.g. compare values in a time series to previous month, same month in the previous year etc.)
* Profiling of data
* Distribution of data
* Plot graphs to quickly visualize a dataset

## Luftqualität

This folder contains a notebook to check the air quality data.
It quickly visualizes all the data to see if there is data missing or makes comparisons to data from previous years.


## Showcases

The showcases notebook compares previously saved data on all packages of our CKAN catalog with the current data retrieved via the API.
Specifically the showcases packages are compared to see if links to dataset went missing (using the `num_datasets` field) or if generally showcases are missing.

## Plausis

This folder contains a collection of different data plausibility checks we usually make before publishing new or updated open data.  This collection contains mainly open data from Statistik Stadt Zürich, e.g. `plausi_BAU` for statistical data on construction (buildings, dwellings, construction activity), `plausi_bev_jahresdaten` for yearly updated statistical data on population or 'plausi_POL' on data on elections and votes in the city of Zurich. Not all of the Jupyter Notebooks have the same quality though ;) But it might help you to get started.

## Biotopkartierung

This repo was used to quickly analyse the very detailed geodataset about the state an quality of biotopes within the City of Zurich. 

## Schulwegübergänge

Also this repo was used to quickly analyse the geodataset about school route crossings. 

