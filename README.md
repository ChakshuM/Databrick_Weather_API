# Databrick_Weather_API
### Databricks Weather API Project Description

The project involves retrieving historical weather data for multiple cities and generating visual insights to support data-driven decision-making. The data collection and visualization process is carried out using the following approach:

1. **Data Retrieval:**
   - **API Integration:** Utilize the Weather API to fetch historical weather data for specified cities.
   - **City List:** Target cities such as Kitchener, Vancouver, Toronto, Niagara Falls, Hamilton, and Edmonton.
   - **Date Range:** Collect data for the past 7 days to analyze recent weather trends.
   - **API Request:** Execute HTTP GET requests to the Weather API, using parameters such as the city name, date, and API key.

2. **Data Processing:**
   - **Code Execution:** Employ Python with libraries like `requests` for API calls, `datetime` for date manipulation, and `pyspark` for data processing.
   - **Data Storage:** Accumulate API responses into a list for further processing.

3. **Data Analysis and Visualization:**
   - **Spark Integration:** Use PySpark to process and transform the collected JSON data into a structured format.
   - **Visualization:** Create visual insights such as temperature trends, precipitation patterns, and other weather-related metrics.
   - **Insights Generation:** Analyze the visual data to derive actionable insights, such as identifying patterns in weather changes or comparing weather conditions across cities.

The project aims to leverage historical weather data to provide valuable insights and visualizations that can assist in understanding weather patterns and making informed decisions based on historical trends.

**Output**

<img width="612" alt="image" src="https://github.com/user-attachments/assets/c509bfaa-19b7-4ec3-8f8d-647eac78fcea">

