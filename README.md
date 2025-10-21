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

<img src="https://github.com/user-attachments/assets/669a4631-6058-4817-b559-9912d3b03a6b" width="600" alt="image" />

**Rides for Popular Companies and Grouping Others**
This query finds the number of rides for the two most popular companies, Flash Cab and Taxi Affiliation Services, during November 1-7, 2017. All other companies are grouped under "Other."

<img src="https://github.com/user-attachments/assets/f67d6b96-b848-4c86-9e60-675a88ea8e89" width="600" alt="image" />
<img alt="Screenshot 2025-10-21 at 3 37 56 PM" src="https://github.com/user-attachments/assets/09978a36-f699-4556-b4a6-7657cc942275" width="600" alt="image" />

**Weather Condition Records by Hour**
This query retrieves hourly weather condition data and classifies each record as "Bad" or "Good" based on whether the description contains the words rain or storm.

<img alt="Screenshot 2025-10-21 at 3 40 38 PM" src="https://github.com/user-attachments/assets/d80a6d9f-dcc9-4839-b03e-cff336570c61" width="600" alt="image" />

**Loop to O'Hare Rides on Saturday**
This query selects rides that started in the Loop and ended at O'Hare on a Saturday, along with their weather conditions and durations. Rides without weather data are excluded.

<img alt="Screenshot 2025-10-21 at 3 53 21 PM" src="https://github.com/user-attachments/assets/352062d9-6f13-4d74-92b2-d52c3614e113" width="600" alt="image" />

## Key Findings
1. **High-Volume Taxi Companies:** Certain companies, such as Flash Cab and Taxi Affiliation Services, account for a significant share of rides, especially during November 1-7.
2. **Weather Influence:** Rides from the Loop to O’Hare Airport on rainy Saturdays tend to have longer durations compared to rides in better weather.
3. **Neighborhood Insights:** Specific neighborhoods show higher ride frequencies, indicating areas where Zuber may focus its resources.

## Conclusion
The data reveals that weather conditions, company reputation, and neighborhood preferences significantly impact ridership in Chicago. Rainy weather, particularly on weekends, affects ride durations, which may be an important factor for Zuber in planning driver availability.

## Recommendations for Improvement

- Expand Data Collection: Collect more detailed data, such as peak hours, vehicle types, and traffic conditions, for a more comprehensive analysis.
- Integrate Real-Time Weather Updates: Zuber can offer flexible pricing or services based on weather predictions to optimize demand.
- Focus on Popular Neighborhoods: Prioritize marketing and driver distribution in high-frequency areas to attract more riders.

## Future Directions
1. **Further Weather Analysis:** Explore the impact of additional weather types (e.g., snow) on ride frequency.
2. **Real-Time Data Integration:** Implement real-time data streaming to enable up-to-date insights for operational efficiency.
3. **Advanced Machine Learning Models:** Use predictive models to forecast ride demand and adjust resource allocation accordingly.

This analysis sets a foundational understanding for Zuber’s market entry and provides actionable insights to enhance service delivery and user experience in Chicago.


