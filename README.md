# DSC180A-Checkpoint
***Note***: To reproduce the results, run `run.ipynb`. The notebook is currently saved in a state that shows the results.

## General Structure of the Repo

## Code
`Run.ipynb` contains code that run to produce the results. Comments have been added to code for explainability.
`my_functions.py` contains the functions that `run.ipynb` uses to produce results.

## Data
The data for this project is stored in `data/.` The raw data files are `data/MTA_Subway_Origin-Destination_Ridership_Estimate__2024_20241008.csv` and `data/MTA_Subway_Stations_updated.csv`, and the processed data files that keeps only the useful columns for the project are `data/ridership.csv` and `data/stations.csv` respectively.

`.gitattributes` is for Git LFS to manage and allow the submission of large data files (i.e. `data/MTA_Subway_Origin-Destination_Ridership_Estimate__2024_20241008.csv` & `data/ridership.csv`)

## Dependencies
The only true dependencies to run the notebook are [Pandas](https://pandas.pydata.org/docs/getting_started/install.html) and [NetworkX](https://networkx.org/documentation/stable/install.html). 
The repo contains `requirements.txt` if one wishes to reproduce the virtual environment the notebook is created in.

