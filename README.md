# nyc-311-service-calls

## Overview
What do New Yorkers need help with? How (and how timely) does the government respond? Let's see if the data has answers.
This project dives into the New York City municipal 311 service call data. Using linear regression, I determine whether response time is correlated with the neighbourhood income level. Data is sourced from https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9.

### Libraries used
1. scikit-learn
2. bokeh
3. pandas

### Visualization
Average monthly response time per zipcode is displayed in an interactive dashboard, programmed with Bokeh. Check it out at http://18.207.2.5:8080/nyc_dash?username=nyc&password=iheartnyc. Linear regression model is currently a work in progress.
