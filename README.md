# NYC Taxi Data Analysis and Modeling

## Overview
This project analyzes and models taxi trip data from New York City, focusing on yellow and green taxis. The analysis includes data preprocessing, exploratory data analysis, and building regression models to predict hourly taxi ride demand in different locations.

## Data
The dataset used in this project is the NYC TLC Taxi Trip Record Data, which includes detailed records of taxi trips such as pickup and dropoff locations, tip amounts, trip distances, and timestamps for both yellow and green taxis.

### Key Steps:
1. **Data Import**: Loading taxi trip data from parquet files.
2. **Data Preprocessing**: Handling missing values, removing outliers, and extracting relevant features such as `pickup_hour` and `pickup_date`.
3. **Exploratory Data Analysis**: Analyzing the distribution of trip counts, tip amounts, and trip distances by hour and taxi type.
4. **Feature Engineering**: Generating features for modeling, including calculating the number of trips per hour per location.
5. **Model Building**: Building and evaluating Linear Regression and Decision Tree Regression models to predict hourly trip counts.

### Results:
The results indicate that Decision Tree Regression outperformed Linear Regression in predicting taxi demand, showing a lower RMSE and higher R² value.

## Installation

### Requirements
To run this project, you'll need the following Python packages:

- pyspark
- pandas
- geopandas
- matplotlib
- seaborn
- numpy

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/nyc-taxi-analysis.git
   cd nyc-taxi-analysis
# homework
