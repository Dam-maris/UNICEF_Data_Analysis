# UNICEF_Data_Analysis
Analysis of mobility data during COVID-19 to evaluate social distancing policy impacts

## Overview of the Project
In order to evaluate the effects of social distancing and mobility reduction measures in a city, this project examines aggregated mobility data gathered during the COVID-19 crisis. The analysis examines various locations, focusses on how mobility patterns have changed over time, and pinpoints vulnerable places with minimal mobility declines.

## The dataset
Three CSV files per day for a week make up the dataset, which represents mobility data at three different time intervals: 
From 0:00 to 8:00**, from 8:00 to 16:00**, and from 16:00 to 0:00**

The following columns are present in every file:
The number of people who used to travel this route before to the crisis is known as the "Baseline: People Moving**.
The number of people seen moving during the crisis is indicated by the **Crisis: People Moving**.
- **x0 / y0**: The area of origin's coordinates.
- **x1 / y1**: The destination area's coordinates.
Internal IDs are **index_0 / index_1**.

## Analysis
The following important topics are included in the analysis:
1. An overview of mobility statistics.
2. Variations in movement throughout time.
3. Determination of poor mobility locations that are at risk.
4. A comparison of the decline in mobility in various regions.

## Visualizations
The project uses a number of visualisations to show the results, including line charts that display changes over time.
Vulnerable locations are highlighted by scatter plots.
A comparison of decrease levels using box plots.

## Start
To perform the analysis:
1. Make a clone of this repository.
2. Launch the `UNICEF_Mobility_Analysis.ipynb` Jupyter Notebook.
3. Verify that the required libraries, such as `matplotlib` and `pandas`, are installed.
4. As directed in the notebook, load the data files.

## Recognitions
I appreciate the chance to take part in the UNICEF Giga Innovation Challenge. I eagerly await your comments.




