# Data cleaning project
#### This is a first version of a jupyter notebook that intent to perform a first look and cleaning of the shark attacks data (attacks.csv) provided by "Global Shark Attack File" website.
## Overview
This project has been develop in order to deliver the second **Ironhack** assignment, and it takes into account some basic parameters from data cleaning.
## Steps
The following are some of the steps that were performed, so that a messy dataset could be turned into a more redable one.
1. **Loading data**: The first jupyter notebook file (loading-data.ipynb) intents to load the data, change the enconding to UTF-8 and create a new csv file (shark_attacks.csv).
2. **Having a first look**: Performing some basic commands in order to get a first insight; for example, looking at shape, columns, data types and null values.
3. **Calculating the missing value percentage**: Computing the percentage of missing value is cricial, both overall and per column. In this step, it's performed that calculation so it could be easier to choose a better approach to carry out the data wrangling process.
4. **Drop null values**: Even though it's say in data analitics that every value and column count, it's way easier and faster to perform the first analisys and visualization if all drop values are dropped. That's what it was done in this step.
5. **Modify and visualize values**: After dropping null values, it's much easier looking inside, modify and clean the dataset and performing some basic visualization. This is what it was performed in this step.