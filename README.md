
# Marathon Winning Times Analysis and Forecasting

This project explores historical data from major marathon events, with a primary focus on the Boston Marathon. The goal is to analyze trends in winning times, understand which countries and genders have dominated, and forecast future winning times using advanced time series models.

## Table of Contents

1. [Dataset](#dataset)
2. [Objectives](#objectives)
3. [Project Steps](#project-steps)
4. [Results](#results)
5. [Getting Started](#getting-started)
6. [Conclusions](#conclusions)
7. [Future Work](#future-work)

## Dataset

The dataset contains historical data from major marathons, including Boston, Berlin, and NYC marathons, covering various years, genders, and countries.

- **File:** `world_marathon_majors.csv`
- **Columns:**
  - `year`: Year of the marathon event
  - `winner`: Winner’s name
  - `gender`: Winner’s gender
  - `country`: Winner’s country
  - `time`: Winning time in `HH:MM:SS` format
  - `marathon`: Name of the marathon event

## Objectives

1. Analyze historical trends in winning times for different marathon events.
2. Explore the dominance of countries and genders in these events.
3. Forecast future marathon winning times, focusing on the Boston Marathon, using the ARIMA time series model.

## Project Steps

### 1. Data Cleaning
- Removed rows with missing data to ensure accuracy.
- Converted the `time` column to a format suitable for numerical analysis.

### 2. Trend Analysis
- Plotted historical winning times to identify trends and patterns.
- Observed a steady decrease in winning times, especially from the 1980s onwards, showing the evolution in athlete performance.

### 3. Country and Gender Analysis
- Aggregated wins by country and gender to see which countries and genders have dominated over the years.
- Visualizations, including bar charts, illustrate total wins by country and cumulative wins by gender over time.

### 4. Time Series Forecasting
- Used an ARIMA model to predict future winning times for the Boston Marathon.
- Trained the model on past winning times and provided confidence intervals to show prediction reliability.

## Results

- **Trend Analysis**: Winning times have generally improved, especially post-1980s, due to advancements in training, competition, and sports science.
- **Country and Gender Dominance**: Countries like Kenya and Ethiopia have led in marathon victories. The gender gap in winning times has narrowed, reflecting the increased competitiveness of female athletes.
- **Forecasting**: The ARIMA model accurately predicted future winning times, with predictions aligning closely to actual times within confidence intervals.

## Getting Started

### Prerequisites

- Python 3.x
- Required Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `statsmodels`



## Conclusions

This project highlights the improvement in marathon performances over the years, with countries like Kenya and Ethiopia leading in the sport. The forecasting model effectively predicts future winning times, providing valuable insights for athletes, coaches, and event organizers.

## Future Work

- Extend analysis to other major marathon events to compare trends.
- Experiment with more advanced models like Prophet or machine learning methods.
- Add more factors, like weather and course difficulty, to improve prediction accuracy.


