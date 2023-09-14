# Understanding the Relationship between Lock Complex Effectiveness and System Performance: A Study of the Volkerak Complex

Welcome to the GitHub page where I share my code for the input & output analysis of my graduation project! Here is the [digitial version of my report](https://repository.tudelft.nl/islandora/object/uuid%3A0933df0a-eb9c-4d64-9f09-5da9b7566ad8?collection=education), if you would like to take a closer look into my motivation for this analysis or the discussion I motivated from this work.

Here is a short description of content in each notebook:

## data_cleaning.ipynb (Data Cleaning & Initial Exploration)
* First look into the operational logs and ship classes
    - unallowed passages, 
    - periods of renovation in lock chambers, 
    - trends in ship characteristics, 
    - passage times and lockages 
* Cleaning the data to get it ready for the prediction. 
* Inspecting malfunctions in the complex.

## validation_locking_regimes.ipynb
Visualizing number of ships per lockage for different locking regimes, comparing them with the real observation.

## arrival_analysis_prediction.ipynb (Analysis and Prediction of Arrivals)
* Identifying arrival pattern
* Work on seasonality
    - Observing seasonality over the years and per ship class
    - Clustering ship classes based on seasonality
    - Fitting SARMA/ARMA models to predict ship arrivals per ship class per direction
* Selecting the week to focus as baseline fleet mix
* Modifying the baseline fleet mix based on IMA, to create the IMA-driven fleet mix

## stress_testing.ipynb
Observing waiting times and emissions under changing fleet intensity and lock condition scenarios.

## univariate_<factor_explored>.ipynb
There are four factors on which univariate experiments are conducted:
1. Chamber priority
2. Inspection duration
3. Inspection start
4. Traffic range
These notebooks generate boxplots of average waiting times and number of levelings for the  univariate experiments.

---

I would appreciate your feedback on how I can improve this repository!
