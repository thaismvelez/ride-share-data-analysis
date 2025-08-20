# Zuber Ride-Share Data Analysis

## Project Overview
This project analyzes ride-sharing data for Zuber, a new ride-sharing company launching in Chicago. The goal is to identify passenger preferences, understand the effects of weather on ride frequency, and provide insights that can help Zuber strategize its services in a competitive market.

## Data Set
The analysis uses a dataset comprising taxi ride records in Chicago, including:

- Neighborhoods: Data on city neighborhoods.
- Cabs: Taxi details and company affiliations.
- Trips: Ride details including start and end times, duration, and distances.
- Weather Records: Weather conditions recorded hourly.

The project will use SQL to perform exploratory analysis and test hypotheses about the impact of weather on ride frequency and duration.

## Introduction
With Zuber's entry into the Chicago ride-sharing market, this project provides data-driven insights into competitor performance and the effects of external factors, such as weather, on ridership trends. These insights will inform Zuber’s strategy to position itself in the market effectively.

## Project Objectives
1. **Explore passenger preferences** by analyzing ride counts across different companies and neighborhoods.
2. **Analyze the impact of weather on ride frequency and duration**, focusing on rainy versus clear days.
3. **Provide recommendations for Zuber's market strategy** based on data-driven insights.

## Methodology 
1. **Data Exploration**:
    - Analyze the frequency of rides for each taxi company during specific periods.
    - Investigate the popularity of rides for companies with “Yellow” or “Blue” in their names.
    - Compare ride counts for major competitors and group other companies as "Other."

2. **Weather Analysis**:
    - Use SQL JOIN operations to link weather conditions to rides based on time.
    - Categorize weather as "Good" or "Bad" based on the presence of rain or storm in the descriptions.
    - Examine the effect of rainy Saturdays on ride duration from the Loop to O'Hare Airport.
  
## Visual Representations
**Taxi Ride Counts by Company**
This query retrieves the number of taxi rides for each company on November 15-16, 2017, sorted by the number of rides in descending order.

