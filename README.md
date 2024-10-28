
Project Overview
This project looks at past data from major marathons, focusing mainly on the Boston Marathon, to understand how winning times have changed over the years. The goal is to find trends in marathon performance and predict future winning times using advanced time series forecasting methods.

Table of Contents
Dataset
Objectives
Analysis Steps
Data Cleaning
Trend Analysis
Country and Gender Analysis
Time Series Forecasting
Results
How to Run the Project
Conclusions
Future Work
Dataset
The dataset includes historical winning times from major marathon events like the Boston, Berlin, and NYC marathons. It covers various years, genders, and countries, providing a broad look at marathon performances over time.

File: world_marathon_majors.csv
Columns:
year: The year the marathon took place.
winner: Name of the winner.
gender: Winner’s gender.
country: Winner’s country.
time: Winning time for the marathon.
marathon: The name of the marathon event.
Objectives
The main goals of this project are:

To look at how winning times in marathons have changed over the years.
To identify which countries and genders have dominated marathon events.
To predict future winning times for marathons using the ARIMA time series model.
Analysis Steps
Data Cleaning
Loaded the dataset and removed rows with missing data to make sure the analysis was accurate.
Converted the “time” column, which was in text format, to a time format that could be used for calculations.
Trend Analysis
Plotted winning times over the years to spot any trends.
Found that winning times have generally gotten faster, especially after the 1980s, showing improvements in athlete performance and race conditions.
Country and Gender Analysis
Counted marathon wins by country to see which countries dominated.
Also analyzed wins by gender to see how male and female athletes' performances have changed over time.
Created bar charts to show total wins by country and cumulative wins over time.
Time Series Forecasting
Focused on the Boston Marathon and used the ARIMA model for time series analysis.
Trained the model on past data to predict future winning times, including confidence intervals to show uncertainty in these predictions.
Created visualizations to compare the model’s predictions with actual results, showing the predictions and confidence ranges.
Results
Trend Analysis: Winning times have become faster and more consistent over the years, especially after the 1980s. This shows better training, advances in sports science, and increased competition.
Country and Gender Dominance: Some countries, like Kenya and Ethiopia, have been particularly successful in marathon running. The gap between male and female winning times has also decreased, reflecting the growing strength of female athletes.
Forecasting: The ARIMA model successfully predicted future winning times for the Boston Marathon, with close matches to actual outcomes and confidence intervals to show prediction reliability.
Conclusions
Marathon performances have significantly improved over the years, and competition has increased.
The ARIMA model proved to be a useful tool for predicting future winning times, offering accurate predictions with measurable uncertainty.
These findings can be helpful for athletes, coaches, and organizers to understand past trends and plan for future performances.
