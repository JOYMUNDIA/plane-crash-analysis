# Airplane Crashes and Fatalities
## by Joy Mundia


## Dataset

> The dataset covered 4962 plane crash instances from years 1908 to 2019. As this was historical data, interpolation and forward-fill were used to fill in any missing values. As most investigation centered around fatalities, columns such as registration number were dropped, as they did not show to be instrumental for investigation. For plane crash summary reasons, a new dataframe was created from the summary column, consisting of word count. As this dataframe was created manually, it was liable to human error. To avoid falsifying information, numerical values associated with the word count were left out in the visualization, and a sequential palette was used instead to show the degree of frequency. 
The dataset was sourced from kaggle and can be accessed [here](https://www.kaggle.com/datasets/cgurkan/airplane-crash-data-since-1908),

## Summary of Findings

> Analysis revealed plane crash fatalities have increased over time, with survival barely scraping 30%. The plane crew are least likely to survive the plane crash compared to the passengers. 
The evenings appear to see the highest fatality count, with the most frequent seasons being summer and autumn due to weather conditions.Individuals are less likely to get killed on the ground even though the most common report on plane crashes involve runway accidents.
Results have compromised accuracy as interpolation used during cleaning may not depict actual results, and summary reports were manually scoured through.

## Key Insights for Presentation

> For the presentation, the main focus will be on the fatalities column.Starting by comparing row-wise instances of those who were onboard the flight, and the number of fatalities associated with that flight. From here I plan to create a new column stating whether all people onboard died, or some survived. This column will serve as mainly the hue parameter throughout the analysis, so as to depict the magnitude of the fatality.
Using the datetime column, the time of day, months and years will be utilized to see the pattern associated with the plane crashes. Whether accidents are seasonal or a mere coincidence.
Finally an appropriate color palette will be used to showcase the most common reasons as numbers can not be used.

