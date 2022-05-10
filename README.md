# Udacity Data Scientist Nanodegree Capstone Project - Starbucks
This is the Capstone project for the Udacity Data Science Nanodegree based on simulated data from the Starbucks rewards mobile app. 

This repository contains all the material to support my final project. 


## Project Overview :
Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). The overall aim of these offers is to reward loyal customers, maximize sales/profit and also gain new customers. 

The typical flow of an offer starts with "Offer Received". The next stage is "Offer Viewed". and the final stage is "Offer Completed", whereby the customer makes a transaction in accordance with the offer viewed. 

There are many challenges inherent in the data, for example: 
  - Some users might not receive any offer during certain weeks
  - Not all users receive the same offer
  - Customers may purchase in any case irrespective of the offer, or without having opened the offer

Throughout the project a number of steps have been added to address these issues.

## Problem Statement :
This project sets out to determine which factors influence the effectiveness of the Starbucks offers. It seeks to identify any other enhancements or observations in customer behaviour that will improve the success rate of marketing offers. It also aims to build a model to look at whether a particular new customer will respond to an offer or not so that future marketing may be better targetted. 

## Packages Used
In order to run the project notebook python 3 needs to be installed and the following packages:

- pandas
- numpy
- math
- json
- matplotlib
- seaborn
- sklearn

## File Structure


This github repo contains
- Starbucks_Capstone_notebook.ipynb: Jupyter notebook for the project.
- Starbucks_Capstone_notebook.html: html version of the Jupyter notebook
- README.md : overview of the project
- License.md : standard license
- \data: folder containing the three Starbucks data files
  - portfolio.json
  - profile.json
  - transcript.json

## Key Findings
- Average spend is highest with females and lowest where we have an unknown classification. When an offer is successful the average spend increases significantly. Interestingly the % increase in spend is largest in the unknown population with a 4-fold increase seen.
- The best offer in terms of increased spend was also found to be the worst in terms of visibility to customers, and represents a missed opportunity. The analysis identified that the lack of social media distribution for this offer was the likely cause.
- The Random Forest model that was developed gives a 70% accuracy on predicting whether an offer will be successful. The 3 most important features in that model were membership length, income and age



## Acknowledgements
Starbucks for the use of their data and support of the nanodegree programme

Stackoverflow for the wealth of knowledge and advice contained on their site

Udacity: This work is part of the data scientist nanodegree capstone project



