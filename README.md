# Uber Drives Data Analysis

## Overview

This Jupyter notebook performs an exploratory data analysis (EDA) of Uber drives data. It covers data cleaning, visualization, and feature engineering to gain insights into Uber trip patterns.

## Dataset

The dataset used is "uberdrives.csv," which contains information about individual Uber trips, including start and end locations, times, purposes, and distances.

## Analysis Steps

1. **Data Import and Cleaning:**
   - Imports necessary libraries (pandas, numpy, seaborn, matplotlib).
   - Loads the dataset into a pandas DataFrame.
   - Cleans the data by handling missing values (imputing "Not Applicable" for trip purpose) and formatting date/time columns.
2. **Exploratory Data Visualization:**
   - Creates various visualizations (countplots, boxplots) to explore trip purposes, categories, start/end locations, distances, and durations.
   - Identifies the most frequent trip purposes, categories, and locations.
   - Analyzes the distribution of trip distances and durations.
3. **Feature Engineering:**
   - Calculates trip durations and adds a "DURATION" column.
   - Extracts day of the week, year, month, and start hour from date/time columns, creating new features.
   - Analyzes trip patterns based on these new features (e.g., trips by day of the week, hour of the day).
4. **Frequent Route Analysis:**
   - Identifies and visualizes the most frequent routes taken by Uber drivers, using both a textual summary and a heatmap.

## Key Findings

* **Trip Purpose:** The most frequent trip purposes are "Meeting," "Meal/Entertain," and "Errand/Supplies," with a significant number categorized as "Not Applicable."
* **Trip Category:** The data predominantly consists of "Business" trips.
* **Location Analysis:** The analysis reveals the most frequent starting and ending locations for the trips, visualized using count plots. Cary appears as a significant starting location, with trip frequency by month also explored.
* **Trip Distance (Miles):** A boxplot shows the distribution of trip distances, with annotations indicating quartiles, medians, minimums, and maximums.
* **Trip Duration:** A new 'DURATION' column was calculated and visualized with a boxplot, showing the distribution of trip times in minutes. Some unusually long durations were noted.
* **Day of the Week and Time of Day:** The number of trips varies across days and hours of the day, with visualizations revealing peak travel times.
* **Temporal Analysis:** Trips were analyzed by year and month, showing trends in travel frequency.
* **Frequent Routes:** The notebook identifies and visualizes the most frequent routes taken, providing insights into popular travel patterns using a textual summary and a heatmap.


## Usage

To run this notebook, you will need:

- Python 3
- Libraries: pandas, numpy, seaborn, matplotlib
- The "uberdrives.csv" dataset

Simply open the notebook in a Jupyter environment (e.g., Google Colab) and execute the cells.


## Author

Aravindan Natarajan
