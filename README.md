# udacity_create_a_tableau_story

## Overview
For this project, I was tasked with creating a Tableau story. 
We were offered a list of datasets to choose from as well as the option to use our own. In this case, I chose a dataset about flights from RITA. 

The dataset was too large to use for Tableau Public (the free version of Tableau). So I subsetted it using python so that I would have a smaller dataset containing only flights starting or ending in the NYC area airports.

## Contents
- 2008_subset.csv - the subsetted dataset
- airports.csv - names of airports (original data only had airport codes); supplied by stat-computing.org
- carriers.csv - names of carriers (original only had tail code abbreviations); supplied by stat-computing.org
- flights_subset.html - HTML-knit of flights_subset.ipynb
- flights_subset.ipynb - Jupyter notebook containing code used to subset original dataset
- Writeup.pdf - more detailed notes on project

## Dataset
This dataset is available publicly at [http://stat-computing.org/dataexpo/2009/the-data.html].

As this dataset was used for a competition, it also links to a data dictionary. 

I used the data from 2008 as my original dataset.
