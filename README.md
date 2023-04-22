<h1 align="left">API AND GET<br><i>Topics: Weather & Geospatial Analysis</i> </h1> 

<p>This project leverages API calls, Python requests, JSON traversals, and pandas/matplotlib data manipulation to analyze weather patterns as we approach the equator and utilize the results to plan future vacations.
</p>

## Data Science Tools
- Python
- Jupyter Notebook
- pandas
- NumPy
- Matplotlib
- Seaborn
- OpenWeatherMap API
- Geoapify API

## Features
- Analyzed over 500 cities with varying distances from the equator.
- Created scatter plots to showcase the relationship between latitude and weather variables (e.g. temperature, humidity, cloudiness, and wind Speed)
- Computed linear regression for each relationship, separating plots into Northern Hemisphere and Southern Hemisphere.
- Planned vacations based on ideal weather conditions using weather data, Geoapify API, and geoViews library.

## Conclusions
- Temperature increases as we approach the equator.
- Other weather variables (humidity, cloudiness, and wind speed) exhibit weaker correlations with latitude.

## Limitations and Future Development
- The dataset may not be entirely representative, as it is based on randomly generated coordinates.
- Each coordinate triggers a separate API call, which may affect performance.
- Enhance the vacation planning feature with additional filters and preferences.
- Integrate additional map visualizations and interactivity.
