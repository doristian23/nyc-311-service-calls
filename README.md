# nyc-311-service-calls

## Overview
What do New Yorkers need help with? How (and how timely) does the government respond? Let's see if the data has answers.
This project dives into the New York City municipal 311 service call data. Do service requests break down into predictable categories? I employ an array of classifiers to find out. Data is sourced from https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9.

### Libraries used
1. scikit-learn
2. bokeh
3. pandas

### Data exploration
Code for calculating correlation between response time and neighbourhood income level can be found in correlation-analysis. Pearson, Spearman, and Kendal values are computed and compared. 

### Visualization
Average monthly response time per zipcode is displayed in an interactive dashboard, programmed with Bokeh. Check it out at http://18.207.2.5:8080/nyc_dash?username=nyc&password=iheartnyc. 
