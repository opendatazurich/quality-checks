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