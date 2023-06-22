# US Population Analysis and Visualization: Project Overview
- The project utilizes the US Census Bureau data available on their website.
- Calculated the total population of the US  by aggregating individual state population data.
- Generated a graph to visualize the growth of the US total population over time using matplotlib.
- Compared California Population with the total US population from 2019.

## Code Used
**Python Version:** 3.9

**Packages:** pandas and matplotlip

## Data Cleaning
After importing the data, I needed to clean it up to use for visualizations. I made the following changes:
- Removed the columns that do not include the 50 states and the District of Columbia.
- Change the Unnamed:0 column name to State.
- Removed the period at the beginning of each state name.
- Removed 2020 columns since they do not represent a whole year in this data.
- Made a new row  at the bottom for the US population.

## Visualizations
This program creates a bar graph to illustrate the US population growth and a pie chart to represent California's population proportion within the US population. Below are these visualizations:
