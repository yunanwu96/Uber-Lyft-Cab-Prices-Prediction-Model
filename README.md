# Uber-Lyft-Cab-Prices-Prediction-Model
Machine learning models used to predict the cab price of Uber &amp; Lyft in Boston, US.

This project aims to analyze cab rides data from Uber and Lyft, along with weather data, to gain insights and solve real-world business problems. The analysis focuses on exploring cab usage patterns, comparing prices between Uber and Lyft, analyzing the impact of time and day on cab prices, and examining the relationship between weather conditions and cab demand.

### 1. Introduction

#### 1.1 Real-world problems

The project addresses the following real-world problems:

1. Cab usage patterns: Analyzing cab usage patterns in the Financial District to understand preferred cab types and ride preferences.
2. Price comparison: Comparing price increments for Uber and Lyft based on ride distance and cab type to help customers make informed decisions.
3. Time and day analysis: Analyzing the most expensive and cheapest times and days to take cabs to optimize trip planning and pricing strategies.
4. Weather and demand analysis: Investigating the impact of precipitation on cab demand and pricing to aid operational planning and trip efficiency.

#### 1.2 Dataset Selection

The project utilizes two datasets from Kaggle:

1. Cab rides dataset: Collected for a week in Nov-Dec 2018 from Uber and Lyft, containing information such as distance, cab type, timestamp, destination, source, price, and surge multiplier. This dataset provides insights into peak hours, popular destinations, price fluctuations, and customer preferences.
2. Weather dataset: Collected hourly for the same week as the cab rides dataset, including variables such as temperature, rain, cloud, pressure, humidity, and wind. This dataset helps analyze the impact of weather conditions on cab ride prices and customer preferences.

#### 1.3 Methodology for data analysis

The data analysis methodology involves the following steps:

1. Data Preparation: Preprocessing the datasets, including handling missing values, duplicates, outliers, transforming timestamps into date-time format, and merging the cab rides and weather datasets.
2. Analysis: Using PySpark, a big data processing framework, to perform distributed data processing tasks. Conducting exploratory data analysis to identify patterns and relationships between variables, answering real-world questions, and generating insights.
3. Visualization: Presenting the findings through visualizations such as tables, charts, and dashboards to facilitate understanding and interpretation of the results.

### 2. Data Preparation

The data preparation process involves cleaning and transforming the cab rides and weather datasets to ensure data quality and compatibility. The steps include:

1. Importing the datasets into Google Drive for easy access in Google Colab using PySpark.
2. Preprocessing the cab rides dataset by handling missing values in the price column, removing duplicates, and addressing outliers in the distance and price columns.
3. Transforming the timestamp column into date-time format for better analysis.
4. Removing unused columns from the cab rides dataset.
5. Performing similar preprocessing steps on the weather dataset, including handling missing values, duplicates, outliers, transforming the timestamp, and removing unused columns.
6. Merging the cab rides and weather datasets based on date-time and location variables, creating separate datasets for source and destination weather conditions to avoid duplications.

### 3. Analysis

The analysis of the combined cab rides and weather dataset focuses on generating insights and answering the real-world problems identified earlier. Key findings include:

#### 3.1 Insight 1: Analysis of Cab Usage Patterns in the Financial District

- Identification of top destinations and sources for cab rides, providing insights into popular areas and commuter hubs.
- Comparison of the popularity of Uber and Lyft cab types.
- Analysis of average prices per mile and distance traveled for both Uber and Lyft, revealing differences in pricing strategies.

#### 3.2 Insight 2: Comparison of Price Increment for Uber and Lyft based on Ride Distance

- Identification of price increments for Uber and Lyft based on ride distance.
- Comparison of price increments between Uber and Lyft to determine which service offers more competitive pricing.
- Visualization of price increment trends for different ride distances to understand pricing patterns.

#### 3.3 Insight 3: Analysis of the Impact of Time and Day on Cab Prices

- Examination of the most expensive and cheapest times and days to take cabs.
- Identification of peak hours and days with high demand and price surges.
- Analysis of pricing variations across different time periods and days of the week.

#### 3.4 Insight 4: Relationship between Weather Conditions and Cab Demand

- Investigation of the impact of weather conditions, such as rain, temperature, and cloud cover, on cab demand.
- Analysis of how weather conditions affect cab prices and customer preferences.
- Visualization of the relationship between weather variables and cab demand.

### 4. Visualization and Reporting

The findings from the analysis will be presented through visualizations and a comprehensive report. The visualizations will include:

- Bar charts and pie charts to illustrate cab usage patterns, preferred cab types, and popularity of destinations and sources.
- Line charts and scatter plots to showcase price increments for Uber and Lyft based on ride distance.
- Heatmaps and line graphs to depict the impact of time and day on cab prices.
- Scatter plots and correlation matrices to visualize the relationship between weather conditions and cab demand.

The report will provide a detailed overview of the project, the methodology used, data preprocessing steps, analysis findings, and insights gained. It will also include recommendations for business strategies based on the analysis results.

### 5. Conclusion

The analysis of cab rides and weather data aims to provide valuable insights into cab usage patterns, price comparison between Uber and Lyft, the impact of time and day on cab prices, and the relationship between weather conditions and cab demand. The project will help stakeholders in the ride-hailing industry make data-driven decisions, optimize pricing strategies, and enhance customer experience based on the identified patterns and trends.