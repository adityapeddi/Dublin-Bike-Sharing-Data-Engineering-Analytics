# Dublin Bike Sharing – Data Engineering & Analytics Case Study
This project presents an end-to-end analysis of Dublin’s public bike sharing stations.
It brings together real-time station information and historical weather observations to explore how environmental and temporal factors influence bike availability and usage across the city.

Repository Structure

API Data Extraction.ipynb	: Notebook for initial data collection, cleaning, and transformation of responses from the JCDecaux bike API, including parsing of nested JSON data.
Bike Usage Analytics.ipynb: Notebook focused on exploratory analysis, visualizations, and insight generation by integrating weather attributes with station-level data.
cleaned_bike_dataset.xlsx: Structured and cleaned dataset generated after flattening and preprocessing the original bike-sharing API data.
cleaned_weather_dataset.xlsx: Processed weather dataset containing refined temperature, rainfall, humidity, and other parameters used for analysis.
merged_bike_dataset.xlsx:	Combined dataset that aligns bike station information with corresponding timestamps for further analysis.
Weather.xlsx:	Raw, unprocessed weather data prior to cleaning.

Key Features of the Project
- API Data Integration
  Real-time station details were retrieved from the JCDecaux public API. The project includes data extraction, transformation, and structuring of nested attributes for analysis.

- Weather Influence Assessment
  Historical weather variables such as temperature, precipitation, humidity, and wind conditions were incorporated to examine how they relate to bike availability and demand.

- Peak Usage Analysis
  Patterns in bike availability were evaluated across typical rush hours and different times of day to understand user behaviour and station load.

- Station Performance Insights
  Stations were compared to identify high-demand and low-usage locations, with observations on possible contributing factors.

  🎯 Project Goals
- Data extraction from APIs
- Data cleaning and preprocessing
- Merging multi-source datasets
- Exploratory data analysis (EDA)
- Interpreting mobility trends influenced by environmental factors

It serves as a practical example of applying data engineering and analytics techniques to a real-world urban mobility scenario.
