# Developing cost-effective, practical, accurate non-weather-based wind power production forecasting AI models

See INSTRUCTIONS.md

**Authors:** Farihah Ahmed (Columbia University) and Mauricio Hernandez (Duke University)

**Mentor:** Mauricio Hernandez

National High School Journal of Science, August 2023 issue, link out soon

**QUICK INTRO:** Efficient methods of wind power production forecasting are crucial for the integration of
renewable energy into the electrical grid. Although many state-of-the-art forecasting models in the field are highly
accurate, most use weather data inputs such as wind speed and direction. However, cost-
effectiveness and practical data collection are not yet widely considered, despite
both being crucial obstacles to the actual deployment of such forecasting models. There are
numerous issues with this weather data which make it costly and impractical. First, deploying
and maintaining a comprehensive network of weather sensors can be challenging and resource-
intensive, requiring significant investments, ongoing maintenance, and expertise to manage &
interpret weather data. Second, professional meteorological agencies and weather data
companies have resources &amp; expertise to collect data at a higher quality and resolution than a
wind power company on its own—and this third-party data tends to be expensive. Third,
processing and interpreting raw data to generate useful power forecasts is a complex task
requiring significant expertise in data science and meteorology—presenting a higher cost for
data processing.

**OUR SOLUTION:** This study hypothesizes that an alternate data source--past power production
data--can be a more cost-effective and practical data source to predict future power production.

**APPROACH**: 10 minutes of past power production data are used to predict the next 10 minutes of future
power production. The open-source ‘Wind Turbine Scada Dataset’ is used from
Kaggle, and are compared with state-of-the-art weather-based models.

**BEST MODELS:** All of the models of this study
outperformed the state-of-the-art models, with the highest r2 score of 0.97 with a
simple neural network. 

**PROJECT IMPLICATIONS:** Thus, by checking all three criteria (high accuracy, cost-effectiveness,
practicality of data collection), we demonstrate a novel, highly efficient alternative for
wind power production forecasting which can be deployed in wind farms quite simply----
accelerating the integration of renewables energy sources into the grid.

 
