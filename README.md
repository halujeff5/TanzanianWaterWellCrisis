# Mod3Final_proj
Tanzanian Water Well Crisis: Predictive Modeling and Analysis

## Repository Content
This repository contains the .csv files I used for my data, 2 jupyter notebooks: 1 with EDA and visualizations and the other with the actual data cleaning, EDA, and modeling process. CleanNB is my notebook with data cleaning, EDA, and modeling process. EDA_Viz_mod3_proj is my other notebook which contains the EDA and graphs and figures used in my presentation slides. The last file in this notebook are the presentation slides.

## Project Scope
The project is a Kaggle competition to discover which of the 57,000 water wells in Tanzania were non functional, functional, or needed repair. The independent features included location, age, issuing entity, and water quality. 

## Data Cleaning / Preprocessing

## Modelling
The top performing model was Random Forest which had a 78-79% F1/Precision Score. We wanted to minimize false positives (saying the well is working when it is not) so actual broken wells were being repaired. Through feature importances, the age of the well was the biggest factor in determining the well status. 
