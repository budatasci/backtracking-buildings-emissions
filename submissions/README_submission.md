# Backtracking Buildings Emissions - Implementation

## Background
According to Boston's Building Emissions Reduction and Disclosure Ordinance (BERDO), organizations with a certain threshold in square footage are required to report the greenhouse gas emissions, energy usage, and energy costs of their buildings. The purpose of BERDO is to make organizations more aware of these factors with the goal of enabling them to reduce all three. For more information on BERDO please refer to their website.

Boston University has decided to report on its entire portfolio of buildings, setting its baseline metrics to 2006. However, since 2006, new buildings have been established on campus, making it impossible to set baseline metrics for them since there is no data dating back to 2006.

## Objective 
To estimate the energy use intensity (EUI) of the new buildings given in the prediction dataset, if they were to have existed back in 2006 using historical data from research buildings.

## Implementation

Using BERDO's public data, we have gathered the EUI for the data in residential and research dataset for the years 2015-2021. 

This would reuslt in the information of the EUI for these buildings in the years 2006 and 2015 to 2021.

While all the data wasn't availbale, for those address whose EUI data was not found, we have estimated the EUI based on similar buiding with the same gross footage.


Data fed to the model: 2015-2021 EUI and the label is the 2006 EUI

## Structure 
```
├── data # summary of data and csv files (Including BERDO datasets used)
├── submissions # add your submission here 
|       ├── submissions.ipynb
|       ├── README_Submission.MD
|       ├── predicted_data.csv
├── README.ME
└── calculate_eui.ipynb # starter code to help calculate the EUI
```

## Results

Refer /submissions/predicted_data.csv 2006 column