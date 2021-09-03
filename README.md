# ds-nanodegree-project-1

This repository contains a jupyter notebook which analyzes a dataset from AirBnb. The dataset used is also included in this project.

## Project motivation

As participant to Udacity's Data Science nanodegree program I'm going to evaluate a dataset from AirBnb activities in Seattle. AirBnb is a company that give people the opportunity to rent an accommodation. Therefore it is interesting to see what is a good price.

In this notebook I'm going to answer the following business questions:

1. What is the price proportion in Seattle?
2. Are there features that influences the price?
3. Which features influence the price at most?


## Requirements

This project needs the following requirement to run:

 - [Jupyter Notebook](https://jupyter.org/) 
 - [Python](https://www.python.org/)

further libraries used
 - numpy
 - pandas
 - matplotlib
 - sklearn
 - seaborn

they will be loaded during to runtime of the notebook and you don't need to preinstall them.


## Files

#### airbnb-seattle.ipynb

A jupyter notebook containing all the steps in this analysis. From reading in the dataset to the final model.

#### seattle/listings.csv

The dataset used in the jupyter notebook.

## Run the project

start the jupyter notebook with following command:
```
jupyter notebook airbnb-seattle.ipynb

```

## Summary of the results of the analysis

This projects includes a trained linear regression model that tries to predict the price. The model receives a r-squared score 0.6, which is not a fantastic score but the best that can be found in that small dataset.

The project clearly evaluates which features have the most impact on the price feature.


## Acknowledgements

The data set used in this notebook can be found on [Kaggle](https://www.kaggle.com/airbnb/seattle/data). Thanks to AirBnb for providing this data.
