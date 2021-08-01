# Mod3Final_proj link to presentation https://jeffreyngds.com/a-regression-analysis-on-national-park-trails-1
Tanzanian Water Well Crisis: Predictive Modeling and Analysis

## Repository Content
This repository contains the .csv files I used for my data, 2 jupyter notebooks: 1 with EDA and visualizations and the other with the actual data cleaning, EDA, and modeling process. CleanNB is my notebook with data cleaning, EDA, and modeling process. EDA_Viz_mod3_proj is my other notebook which contains the EDA and graphs and figures used in my presentation slides. The last file in this notebook are the presentation slides.

## Project Scope
The project is a Kaggle competition to discover which of the 57,000 water wells in Tanzania were non functional, functional, or needed repair. The independent features included location, age, issuing entity, and water quality. The well status was the dependent variables. 

## Data Cleaning / Preprocessing

## EDA
From data, 50% of wells are not servicing their communities. About 13,000 out of the 57,000 pumps fail within 20 years and nearly all fail with 30 years. Since a major reconstructive effort took place in 2000, right now would be a pivotal time for repairs since it has been 20 years. Gravity and hand pump types broke down with the highest frequency indicating that we should avoid installing these types in the future. Through EDA in feature importance we found that the region of the well was an important factor in its class suggesting that certain areas of the country were neglected by the government. Upon closer analysis, altitude had a large determining factor in pump repair suggesting if the location was hard to access, the pump would be neglected.


## Modelling
The top performing model was Random Forest with Recursive Feature Elimination and Cross Validation (RFECV) which had a 78-79% F1/Precision Score. We wanted to minimize false positives (saying the well is working when it is not) so actual broken wells were being repaired. Through feature importances, the age of the well was the biggest factor in determining the well status. 
