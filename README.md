# Data preprocessing - NYC Motor Vehicle Crashes Project

<img src="https://github.com/Louan-M/nyc-crashes/blob/main/Images/boroughs_NYC.png" width="550">

## What ?

This project consists of cleaning and preprocessing a dataset containing the daily reported Motor Vehicle Collisions/crashed that occured in New York City.

More info about the dataset can be found [here](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95).

The final goal is to deliver a cleaned dataset that will be process by a ML model for predicting the dangerosity of the streets.

## Who ?

Carried out by **Louan Mastrogiovanni**,  Theano 2.27 promotion @BeCode


## Why ?

- Consolidate knowledge of pandas/numpy libraries and learn how to clean and preprocess a dataset
- Adapt the process to the final goal (ML model)

## When ?

This is a 2 days project. The dead line is on `10/03/2021 05:00 PM`.

## How ?

### Overal process
1) Drop the columns that have too much NaN values
2) Fill in the missing Zip code and borough. These data were considered particularly relevant for the ML model. A use of an API (geocode ArcGIS) was necessary for this task.
3) Consolidate the addresses into a single column. 
4) Further cleaning + preprocessing (drop columns not needed anymore, replace NaN values, drop unecessary rows, change types, ...)

## About the repository

This repository contains the cleaned dataset `Final_dataset.csv` and the source code (Notebook) `NYC_crashes_project.ipynb`. 

*Shape of `Final_dataset.csv` :* 
&nbsp;
**(92046 rows x 22 columns)**
&nbsp;
## Thank you for reading!
